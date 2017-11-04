# pc-docs

Pioneer Coders website test scenarios.

# Test Scenarios

## Login test scenarios

| S.No | Scenario           |  Steps  |  Expetcted Result   |  Success/ Error Message  |
| ------------- |-------------| -----| -----|  -----|
| 1 | Login With valid credintials | 1) Click on login button <br> 2) login popup should show <br> 3) enter valid email and password  | User should land on desktop page |   |
| 2 | Login With invalid credintials | 1) Launch Login popu <br> 2) Enter in valid credetials      | Login should Failed with error message   |  Invalid credentials |

## Forgot password test scenarios

| S.No | Scenario           | Expetcted Result   |  Success/ Error Message  |
| ------------- |:-------------:| -----:|  -----:|
| 1 | Forgot password | User should land on change password page <br> after entering emails id, password change link should go to the mail    |   |
| 2 | Login With invalid credintials <br> (invalid user or invalid pwd)      | Login should Failed with error message   |  Invalid credentials |

## Tutorials  test scenarios
  
| S.NO | Scenario                 | Success/ Error Messages  |
| ---- |:-------------:| -----:|
| 1    | Get Tutorial by top name  | It should return tutorial conternt for that topic | 
| 2    | Get Tutorial by top name </br> no tutorial file in backend. | it should return the content not avaliable html file. |






