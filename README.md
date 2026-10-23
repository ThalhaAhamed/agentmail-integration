# MeetStream AgentMail Integration

Connect a MeetStream meeting agent to [AgentMail](https://www.agentmail.to) so the agent can send and receive email from its own inbox.

[AgentMail](https://www.agentmail.to) is an email API for agents: create an inbox, send a message, and read replies. This repository is the MeetStream side of that connection. After a call, the agent can mail a follow-up from its own address, and when someone writes back, that reply can be handed to the agent.

## Status

This repository is being initialized. There is no client, webhook handler, or example to run yet. Setup and usage will be added as the integration is built.

## Repository scope

- An inbox for a MeetStream agent, created through AgentMail.
- Sending mail from the agent, including a follow-up after a meeting.
- Receiving replies and handing them back to the agent.
- Configuration for an AgentMail API key. Keys stay out of this repository.

## About MeetStream

[MeetStream](https://meetstream.ai) is meeting bot infrastructure. A bot joins Google Meet, Zoom, or Microsoft Teams, records the call, and can run a MIA voice agent inside the meeting.

## Links

- AgentMail: https://www.agentmail.to
- AgentMail docs: https://docs.agentmail.to
- MeetStream: https://meetstream.ai
- MeetStream docs: https://docs.meetstream.ai
- GitHub: https://github.com/meetstream-ai
