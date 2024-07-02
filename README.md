# oc-logistics
i want to overcomplicate my minecraft factories

## resource monitor
### SERVER
- get realtime readout of select storage contents
  - read from configurable file
  - integrated gui to reconfigure?
  - change refresh rate?
  - variable refresh for sending non-alert packets to clients?
- display readout to user
  - cool ui?
  - allow pushing to connected screens
- alert if numbers get too high or low
  - also configure within ui?
  - push alert packets to clients

### CLIENT
- inform user of alerts
  - can tablets beep?
  - only beep every now and then and not on every packet in
  - controls to snooze and manually resolve alerts?
  - display thing being alerted about obviously
- display readout as well
  - different less priority packet than alert
  - screen control? allow main server to send packets which are mirrored by subservers elsewhere on local network? good for display at scale due to component limitations
- edit config remotely
  - low priority but would be pretty cool
