# poecile

This project is a Telegram master bot that allows users to create, manage, and control their own simple Telegram bots. It provides basic functionality for user registration, bot creation, and bot management through an easy-to-use command interface.

## Features
- **User Registration**: Users can register themselves via the `/start` command.
- **Create Bots**: Users can create their own simple echo bots using the `/create_bot <TOKEN>` command.
- **List Bots**: View all the bots a user has created with the `/list_bots` command.
- **Delete Bots**: Users can delete their bots using the `/delete_bot <BOT_ID>` command.
- **Database Integration**: All data is stored in a PostgreSQL database, managed through SQLAlchemy.

## Tech Stack
- **Python**: Main programming language.
- **Aiogram**: Telegram bot framework.
- **SQLAlchemy**: ORM for database management.
- **PostgreSQL**: Database for storing users and bots.
