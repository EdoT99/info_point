### 🛑 Check this before any action!

```mermaid
graph TD
    Start([I have a question!]) --> Search{Did I search for<br>the answer first?}
    Search -- No --> SearchAgain[Try Wiki, Google,<br>or Docs first]
    Search -- Yes --> Peer{Could a peer<br>answer this?}
    Peer -- Yes --> AskPeer[Send a Slack/Message]
    Peer -- No --> Urgent{Is it an<br>Emergency?}
    Urgent -- No --> Schedule[Add to next 1-on-1<br>or send Email]
    Urgent -- Yes --> Headphones{Are they wearing<br>headphones?}
    Headphones -- Yes --> Wait[Come back in<br>30 minutes]
    Headphones -- No --> Enter([KNOCK GENTLY])