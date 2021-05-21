# async_mongo_logger
An async logger for mongodb

# Usage

logger = Logger(name='nice_logger', client=motor_client, database='logs', collection='fancy_collections', log_to_console=True)
logger.info('the very important log message')