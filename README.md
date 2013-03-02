plog makes it easy to run processes and send their output to the logging
system. For example

    import plog
    import logging

    logging.basicConfig(level=logging.INFO)

    process = plog.LoggedProcess(["ls"])
    process.execute()
