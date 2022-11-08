
mode:
audit = trigger on cloud logging api call
periodic = trigger on cloud scheduler
pull = trigger on CLI command
scc = trigger on Security Command Center finding

action:
notify = identify and send an email about the malformed resource
update = identify and update the malformed resource
delete = identify and delete the malformed resource
report = one-off CLI report of malformed resources