# vue-ios-timer

> A IOS style time picker based on Vue and better-scroll

## Installation
    npm i better-scroll --save
    npm i vue-ios-timer --save

## Setup iosTimer
    import Vue from 'vue'
    import vueIosTimer from 'vue-ios-timer'

## Useage
    <ios-timer type="datetime" ref="timer" datetime="2018-10-10 08:30"  @getTime="getTime"></ios-timer>
    this.$refs.timer.show()

## Constructor options
 |key|descriptions|default|options|
 |:---|---|---|---|
 |`type`|The three type is optional|datetime|date,datetime,time|
 |`confirmText`|confirmText|确定|any|
 |`cancelText`|cancelText|取消|any|
 |`date`|start date|new Date()|like '1990-10-10' format|
 |`datetime`|start datetime|new Date()|like '1990-10-10 08:30' format|
 |`time`|start time|new Date()|like '08:30' format|
 |`getTime`|callback|none|none|
 |`show`|method:show timer|none|none|


## License
[The MIT License](https://opensource.org/licenses/MIT)








