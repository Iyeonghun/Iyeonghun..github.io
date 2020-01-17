---
title: Mi Band UUID
layout: entry
description: Mi Band UUID 분석 자료
tags: [Mi Band, 미밴드]
published: false
comments: true
---

## Mi Band 1 UUID

작성중

<br>

## Mi Band 2 UUID

##### Generic Access Service

- service :: with UUID=00001800-0000-1000-8000-00805f9b34f  
  - characteristic :: with UUID=00002a00-0000-1000-8000-00805f9b34fb	
    - Device Name
  - characteristic :: with UUID=00002a01-0000-1000-8000-00805f9b34fb
    - Apperance
  - characteristic :: with UUID=00002a04-0000-1000-8000-00805f9b34fb
    - Peripheral Preferred Connection Parameters(주변 기본연결 매개변수)

##### Generic Attribute Service

- service :: with UUID=00001801-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00002a05-0000-1000-8000-00805f9b34fb
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb

##### Device Information

- service :: with UUID=0000180a-0000-1000-8000-00805f9b34fb 
  - characteristic :: with UUID=00002a25-0000-1000-8000-00805f9b34fb 
    - Serial Number String
  - characteristic :: with UUID=00002a27-0000-1000-8000-00805f9b34fb
    - Hardware Revision
  - characteristic :: with UUID=00002a28-0000-1000-8000-00805f9b34fb
    - Software Revision
  - characteristic :: with UUID=00002a23-0000-1000-8000-00805f9b34fb
    - System ID
  - characteristic :: with UUID=00002a50-0000-1000-8000-00805f9b34fb
    - PnP ID

##### Unknown Service

- service :: with UUID=00001530-0000-3512-2118-0009af100700
  - characteristic :: with UUID=00001531-0000-3512-2118-0009af100700
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00001532-0000-3512-2118-0009af100700


##### Alert Notification Service

- service :: with UUID=00001811-0000-1000-8000-00805f9b34fb

  - characteristic :: with UUID=00002a46-0000-1000-8000-00805f9b34fb
    - New Alert
  - characteristic :: with UUID=00002a44-0000-1000-8000-00805f9b34fb
    - Alert Notification Control Point


  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb


##### Alert Service

- service :: with UUID=00001802-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00002a06-0000-1000-8000-00805f9b34fb
    - Alert

##### HeartRate Service

- service :: with UUID=0000180d-0000-1000-8000-00805f9b34fb

  - characteristic :: with UUID=00002a37-0000-1000-8000-00805f9b34fb
    - HeartRate Measurement


  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00002a39-0000-1000-8000-00805f9b34fb
    - HeartRate Control Point

##### Mi band Service

- service :: with UUID=0000fee0-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00002a2b-0000-1000-8000-00805f9b34fb
    - Current Time
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00000001-0000-3512-2118-0009af100700
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00000002-0000-3512-2118-0009af100700
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00000003-0000-3512-2118-0009af100700
    - ?????? 이건 아닌듯?
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00002a04-0000-1000-8000-00805f9b34fb
    - Peripheral Preferred Connection Parameters(주변 기본연결 매개변수)
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00000004-0000-3512-2118-0009af100700
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00000005-0000-3512-2118-0009af100700
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00000006-0000-3512-2118-0009af100700
    - ?????? Listener?
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00000007-0000-3512-2118-0009af100700
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00000008-0000-3512-2118-0009af100700
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=00000010-0000-3512-2118-0009af100700
  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb

##### Mi band Service

- service :: with UUID=0000fee1-0000-1000-8000-00805f9b34fb

  - characteristic :: with UUID=00000009-0000-3512-2118-0009af100700
    - ?????? Listener? {18, 0, 1}


  - descriptor :: with UUID=00002902-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=0000fedd-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=0000fede-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=0000fedf-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=0000fed0-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=0000fed1-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=0000fed2-0000-1000-8000-00805f9b34fb
  - characteristic :: with UUID=0000fed3-0000-1000-8000-00805f9b34fb
