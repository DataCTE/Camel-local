# Camel-local

This script is designed to work with models available in the GPT4All catalog. It facilitates interactive conversations between an assistant and a user using the CAMELAgent class and langchain library. The script allows for specifying tasks, generating more specific tasks, and initiating conversations based on those tasks. The conversation alternates between the user providing instructions and the assistant generating responses. The script includes functionality for tracking model usage, estimating cost, and saving conversations.
How to Change the Script

    Model Selection: The script is specifically designed to work with models available in the GPT4All catalog. To incorporate different models, modifications are required to ensure compatibility with the langchain library and to adapt the prompts and logic accordingly.

    Task Specification: Modify the task variable to specify the initial task. You can customize the template used for task specification in the task_specifier_prompt variable.

    Conversation Flow: Adjust the prompts and messages used in the conversation by modifying the assistant_inception_prompt and user_inception_prompt variables. Customize the conversation instructions and formats as per your use case.

    Conversation Length: Set the desired chat_turn_limit to determine the maximum number of conversation turns before the script exits. Adjust this value based on your requirements.

    Saving Conversations: Customize the write_conversation_to_file function to specify the file name and path for saving the conversation. Modify the format and content of the saved conversation as needed.

    Additional Functionality: Extend the script with additional features or callbacks from the langchain library to enhance the conversation flow or add specific functionalities based on your project requirements.

Supported Models

This script specifically supports models available in the GPT4All catalog. To use different models, you would need to modify the script to ensure compatibility with the langchain library and adapt the prompts and logic accordingly.
- DataCTE
