# Backend Application

This directory contains the backend application for the project. The backend is built using [Quart](https://quart.palletsprojects.com/), a Python framework for asynchronous web applications.

## Structure

The main application file is [`app.py`](app/backend/app.py). This file sets up the Quart application and defines the routes.

The `approaches` directory contains different RAG (Retrieval Augmented Generation) approaches for the Chat and Ask tabs of the application.

## Running the Application

To run the application, you can use the "Python: Quart" configuration in the [`.vscode/launch.json`](.vscode/launch.json) file. This will start the Quart application in debug mode.

You can also start the application using the "Start App" task in the [`.vscode/tasks.json`](.vscode/tasks.json) file.

## Customization

For more details on customizing the backend, see the [customization guide](docs/customization.md).

## Testing

Tests for the backend application can be found in the `tests` directory at the root of the project.

To run the tests, you can use the "Python: Run All Tests" configuration in the [`.vscode/launch.json`](.vscode/launch.json) file. This will run all the tests in the project.

You can also run the tests using the "Run Tests" task in the [`.vscode/tasks.json`](.vscode/tasks.json) file.

For more details on writing tests, see the [testing guide](docs/testing.md).

## Deployment

For deployment instructions, see the [deployment guide](docs/deployment.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

The following code snippet shows the content of the `docs/customization.md` file:

```markdown
# Customization Guide

This guide explains how to customize the backend application for the project.

## Structure

The main application file is [`app.py`](../app/backend/app.py). This file sets up the Quart application and defines the routes.

The `approaches` directory contains different RAG (Retrieval Augmented Generation) approaches for the Chat and Ask tabs of the application.

## Customizing the Backend

To customize the backend, you can modify the following:

1. **Routes**: You can modify the routes defined in the `app.py` file.

2. **RAG Approaches**: You can add new RAG approaches to the `approaches` directory and update the routes in the `app.py` file to use the new approaches.

3. **Configuration**: You can update the configuration settings in the `config.py` file.

4. **Logging**: You can configure logging in the `logging.conf` file.

## Adding a New RAG Approach

To add a new RAG approach, follow these steps:

1. Create a new Python file in the `approaches` directory.

2. Implement the RAG approach in the new file.

3. Update the routes in the `app.py` file to use the new approach.

## Running the Customized Backend

To run the customized backend, follow the instructions in the [README.md](../README.md) file.

## License

This project is licensed under the MIT License - see the [LICENSE](../LICENSE) file for details.
```

The following code snippet shows the content of the `docs/testing.md` file:

```markdown
# Testing Guide

This guide explains how to write and run tests for the backend application