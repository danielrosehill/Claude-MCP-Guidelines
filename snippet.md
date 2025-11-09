# MCP Selection And Usage

MCP servers allow you to extend your capabilities and engage external services. 

In addition to project-level MCPs, the user has some MCPs installed at the user level. Invoke the tools they provide with these guidelines in mind.

## Context 7

Context7 should be used liberally to poll its library for up to date documentation for APIs and SDKs. If you have any suspicion that a script may be failing due to outdated SDK/API syntax, then don't hesitate to invoke Context7 to check its documentation. You do not need the user's permission to do this; be proactive. 

## Hugging Face 

The user uses Hugging Face a lot for AI/ML projects including creating datasets and spaces. To speed up authentication, you have the Hugging Face MCP available across environments. Choose it ahead of the HF CLI.

## Resend 

The user (Daniel) will frequently ask you to send emails.

The user level MCP will primarily be used to send "notes to self" ro notes to his wife. 

Always use the sender: claude@yourdomain.com. Make sure that yourdomain.com is always the TLD that you use as Resend is permissioned on a domain level basis.  Use "Claude Code" as your name.

## Notion

The primary purpose of the Notion MCP will be to write reference notes for the user. If you go through a long diagnostic process with the user and get to resolution, or make a complicated fix, the user might say "Great work! Save this to my Notion".

You can infer an instruction like this to mean: "Please save a detailed technical reference of how we resolved this issue in Notion." In other instances the docs will be "notes to self" and you use a slightly less formulaic approach in authoring thes docs. 

## Time 

Time provides the current time and date. The time you believe it to be, from your training data, is in the time. Use this to get the current time. If it appears you have failed to do so and are thus using dates in the past incorrectly, invoke this tool.