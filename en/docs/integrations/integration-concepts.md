# Integration Concepts
Choreo integrations allow you to create enterprise integrations to automate workflows in a user-friendly low-code environment. Here are some basic concepts which will help you understand Choreo integrations as you develop your integrations in the [Choreo Console]({{choreo_console}}).
  
## Integration
Integration in Choreo is a process that connects APIs, events, and streams allowing these to function as a single unit. Choreo provides an integration template which is a pre-built sample designed to address a common integration requirement. Choreo includes a set of comprehensive integration templates for you to select and use.

## Trigger
A trigger in Choreo integrations is an event or an action that causes a Choreo integration to start executing.

Choreo supports the following trigger types:

 - **Schedule**: Triggers execution according to a given schedule.
 - **Manual**: Triggers execution manually.
 - **Calendar**: Triggers execution based on events in a Google Calendar.
 - **GitHub**: Triggers execution based on GitHub events and actions.
 - **Salesforce**: Triggers execution based on Salesforce events. 

## API call
An API call in Choreo allows you to connect to an external service through your Choreo integration. You can use an API call to interact with generic protocol-based APIs and application-specific APIs.

The following lists the connections you can use to interact with generic protocol-based APIs:
  
 - **HTTP**: Communicates with external endpoints over HTTP.   
 - **SMTP**: Performs email-related operations over SMTP. 
 - **POP3**: Retrieves emails from a mail server over POP3. 
 - **IMAP**: Retrieves emails from a mail server over a TCP/IP connection.

The following lists the connections you can use to interact with application-specific APIs:

 - **Twilio**: Integrate with Twilio to perform operations such as sending messages, WhatsApp messages, and making voice calls.
 - **Slack**: Integrate with Slack to perform operations such as sending a message to a channel, deleting a message, etc.
 - **GitHub**: Integrate with GitHub to perform operations such as creating an issue, creating a pull request, etc. 
 - **Gmail**: Integrate with Gmail to perform operations such as sending an email, receiving an email, etc.
 - **Google Calendar**: Integrate with Google Calendar to perform operations such as creating an event, deleting an event, etc.
 - **Google Sheets**: Integrate with Google Sheets to perform operations such as reading data, formatting data, etc.
 - **Salesforce**: Integrate with Salesforce to perform operations such as obtaining organization information, creating a record, etc.
 - **NetSuite**: Integrate with Netsuite to perform operations such as creating a record instance, creating a sublist, etc. 

## Statement

A statement is a collection of code fragments that specifies the actions to be carried out by a Choreo integration. Choreo statements can also be composed of expressions. These expressions are written based on the [Ballerina Expression Syntax](#ballerina-expression-syntax).

Choreo supports the following statements:

 - **Log**: Logs an event with an information statement or an error that occurs in your Choreo integration.
 - **Variable**: Declares a variable and a value of a preferred data type (`string`, `int`, etc.) to use later in the logical process of the Choreo integration.
 - **If**: Performs conditional execution.
 - **ForEach**: Includes a control flow statement in your Choreo integration to iterate over a list of items.
 - **While**: Continuously executes a block of statements in a loop based on a given `boolean` condition. 
 - **Respond**: Sends a specific response back to the client. For example, if the request was processed successfully,  responding to the client with an `HTTP_OK`.
 - **Other**: Allows to write a single or a multiline code snippet in your Choreo integration.

## Ballerina expression syntax
The syntax to use when you want to input values for an expression while designing an integration using Choreo. [Refer to the syntax.](../references/ballerina-expression-syntax)
