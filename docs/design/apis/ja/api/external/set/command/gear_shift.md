# /api/external/set/command/gear_shift

## Classification

- Category: Optional
- Behavior: Topic
- DataType: [autoware_external_api_msgs/msg/GearShiftStamped](https://github.com/tier4/autoware_api_msgs/blob/develop/autoware_external_api_msgs/msg/GearShiftStamped.msg)

## Description

車両の変速機を制御するコマンドを送信する。

## Requirement

現在の車両状態を考慮し、指定されたコマンドを可能な限り反映した制御を行うこと。
