# Home Assistant Add-On: Agent DVR

## How to use

The user manual for iSpy Agent DVR can be found here: [https://www.ispyconnect.com/userguide-agent-dvr.aspx](https://www.ispyconnect.com/userguide-agent-dvr.aspx)

### [Storage Management](https://www.ispyconnect.com/userguide-agent-storage-management.aspx)
The add-on is a docker container based on this docker container: [ispyagentdvr-docker](https://github.com/doitandbedone/ispyagentdvr-docker). By default, the default folder of Agent DVR is persistent, but not accessible anywhere externally.

To solve this problem, there are two options:
1) add an extra storage location, pointing to a folder in the `/share` folder
2) use the override switch to link the default folder of Agent DVR to a folder `/share`. The name of the new folder can be given in the configuration of the addon.
