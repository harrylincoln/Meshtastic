---
id: canned-message-plugin-settings
title: Canned Message Plugin Settings
sidebar_label: Canned Message Plugin Settings
---
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';


## Overview

The CannedMessage Plugin will allow you to send messages to the mesh network
from the device without using the phone app.
You can predefine text messages to choose from.

Please also follow settings of Rotary Encoder to configure input source!

## Settings

| Setting | Acceptable Values | Default |
| :-----: | :---------------: | :-----: |
| canned_message_plugin_enabled | `true`, `false` | `false` |
| canned_message_plugin_allow_input_source | `string` | `_all` |
| canned_message_plugin_messages | `string` | (not defined) |
| canned_message_plugin_send_bell | `true`, `false` | `false` |

### canned_message_plugin_enabled

Enables the plugin.

### canned_message_plugin_allow_input_source

Input event origin accepted by the canned message plugin.
Can be e.g. "rotEnc1" or keyword "_any"

### canned_message_plugin_messages

Predefined messages for CannedMessagePlugin separated by '|' characters.

You can define up to 50 messages with a total length 1024 bytes.

### canned_message_plugin_send_bell

CannedMessagePlugin also sends a bell character with the messages.
ExternalNotificationPlugin can benefit from this feature.

## Details

See "Software / Plugins / Canned messages" for details! 

## Examples

See "Software / Plugins / Canned messages" for examples! 
