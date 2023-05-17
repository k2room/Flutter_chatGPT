# chatgpt

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:


### TroubleShooting
Fix chat_gpt_sdk-2.1.3 library.

In chat_gpt_sdk/lib/src/model/chat_complete/request/chat_complete_text.dart 51th line:
  final List<Map<String, String>> messages; =>  
  final List<Map<String, dynamic>> messages;