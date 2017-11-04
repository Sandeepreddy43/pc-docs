# pc-docs

Pioneer Coders website test scenarios.

# Test Scenarios

## Login test scenarios

| S.No | Scenario           |  Steps  |  Expetcted Result   |  Success/ Error Message  |
| ------------- |-------------| -----| -----|  -----|
| 1 | Login With valid credintials | 1) Click on login button <br> 2) login popup should show <br> 3) enter valid email and password  | User should land on desktop page |   |
| 2 | Login With invalid credintials | 1) Launch Login popup <br> 2) Enter in valid credetials      | Login should Failed with error message   |  Invalid credentials, Please check email and password. |

## Forgot password test scenarios

| S.No | Scenario           |  Steps  |  Expetcted Result   |  Success/ Error Message  |
| ------------- |-------------| -----| -----|  -----|
| 1 | Forgot password | 1) Launch  login popup <br> 2) Click on forgot password <br> 3) On Forgot password page enter valid registered email id <br> 4) Password reset page url shold send to mail <br> 5) Open mail and click the reset password url. it shold land on password reset page. <br> 6) Enter new password. | Password should be able to reset. |   |

## Tutorials  test scenarios
  
| S.NO | Scenario                 | Success/ Error Messages  |
| ---- |:-------------:| -----:|
| 1    | Get Tutorial by top name  | It should return tutorial conternt for that topic | 
| 2    | Get Tutorial by top name </br> no tutorial file in backend. | it should return the content not avaliable html file. |






