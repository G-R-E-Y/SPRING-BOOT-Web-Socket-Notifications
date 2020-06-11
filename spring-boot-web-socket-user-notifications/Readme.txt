WebSocket to build an interactive web application
-------------------------------------------------

Simple (or Streaming) Text Oriented Message Protocol (STOMP), formerly known as TTMP, is a simple text-based 
protocol, designed for working with message-oriented middleware (MOM). It provides an interoperable wire f
ormat that allows STOMP clients to talk with any message broker supporting the protocol. 

It is thus language-agnostic, meaning a broker developed for one programming language or platform can 
receive communications from client software developed in another language.


Create a resource representation class
-------------------------------------
We  can create the  STOMP message service.The service will accept messages containing a name in a STOMP message whose body is a JSON object. 

{
    "message": "hello"
}

-> Class Notification


@EnableWebSocketMessageBroker enables WebSocket message handling, backed by a message broker.

