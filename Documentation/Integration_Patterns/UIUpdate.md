[Table of Contents](../Documentation.md)

# UI Update Based on Data Changes

## Description


## Solutions

The recommended solution to this integration problem is to use the Salesforce Streaming API. This solution is composed of the following components:
A PushTopic with a query definition that allows you to:
Specify what events trigger an update
Select what data to include in the notification
A JavaScript-based implementation of the Bayeux protocol (currently CometD) that can be used by the user interface
A Visualforce page or Lightning component
A JavaScript library included as a static resource


## Sequence Diagram

![UI Update](../../Images/UIUpdate-SeqDiagram.png)


