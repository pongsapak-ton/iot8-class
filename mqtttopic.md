## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301020/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301020/model-01/sn-001
    - payload
        - {"temperature": "25.2"}
        - {"load-senser": "20Kg"}
        - {"water-level": "60L"}
        - {"filter-clockage": "60d"}
        - {"door-senser": "close"}
        - {"speed-motor": "60m/s"}
        - {"Humidity": "30.5"}
        - {"energy-sensor": "60w"}
        

 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301020/model-01/sn-001
    - payload
        - {"presence detection": "20%"}
        - {"Humidity": "40.3"}
        - {"Air-pressure": "40%"}
        - {"temperature": "30.6"}
        - {"light-senser": "40%"}
        - {"name": "value"}
        - {"name": "value"}



