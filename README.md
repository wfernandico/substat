#### ETR_ACTION_CONFIGHRCOM
Dictionary for what ACTION was done.

#### ETR_CONTEXT_CONFIGHRCOM
A CONTEXT is an APP and NAME combined.<br>
ID is CONTEXT_ID in other tables.
#### ETR_CONTEXT_SUMHRCOM
EVENT CONFIG per CONTEXT CONFIG per YYYYMMDD sums.

#### ETR_ERRORLOGHRCOM

#### ETR_EVENTHRCOM
##### ETR_EVENT_CONFIGHRCOM
Consider this the umbrella dictionary.<br>
ID is EVENT_CONFIG_ID in other tables.<br>
TARGET_CONFIG_ID references ETR_TARGET_CONFIGHRCOM.<br>
INITIATOR_CONFIG_ID references ETR_INITIATOR_CONFIGHRCOM.<br>
ACTION_CONFIG_ID references ETR_ACTION_CONFIGHRCOM.<br>
Consider tying this to: ETR_INITIATOR_SUMHRCOM

#### ETR_EVENT_LOGHRCOM
Registers page activity/traffic in the tradeshow.<br>
TARGET_ID is equivalent to the TRADESHOW_ID.

##### ETR_EVENT_SUMHRCOM

#### ETR_INITIATOR_CNTHRCOM
Sums the total EVENT CONFIG done per YYYYMMDD.
#### ETR_INITIATOR_CONFIGHRCOM
Basically ID's the INITIATOR as regular/guest/manager.
#### ETR_INITIATOR_SUMHRCOM
Sums the total EVENT CONFIG done per INITIATOR per YYYYMMDD.

#### ETR_OBJECT_COUNTHRCOM
Empty
##### ETR_OBJECT_COUNT_TOTALHRCOM
TARGET CONFIG per CONTEXT CONFIG per CONTEXT sums.

#### ETR_TARGET_CONFIGHRCOM
Dictionary for target NAME and APP they're housed.<br>
ID is TARGET_CONFIG_ID in other tables.
#### ETR_TARGET_SUMHRCOM
