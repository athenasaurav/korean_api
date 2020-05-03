## path_지하철호선
* greet
  - utter_greet
* 지하철호선{"STATION": "안심"}
  - slot{"STATION": "안심"}
  - action_station

## sad path 1
* greet
  - utter_greet

## path_지하철호선
* greet
  - utter_greet
* 지하철호선{"STATION": "안심"}
  - slot{"STATION": "안심"}
  - action_station


## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot


## path_지하철호선
* greet
  - utter_greet
* 버스노선{"FROM": "아양교", "TO":"아양교"}
  - slot{"FROM": "아양교", "TO":"아양교"}
  - action_bus_station

## path_지하철호선
* greet
  - utter_greet
* 버스노선{"FROM": "해안", "TO":"해안"}
  - slot{"FROM": "해안", "TO":"해안"}
  - action_bus_station