# cognicity-reports-telegram
Telegram support for CogniCity GRASP

### Install
`npm install`  
make sure that node is updated, otherwise you'll get es6 warnings/errors.  
`node -v` should be at least ~0.7.4  

### Run
`node app.js`

### .env
Save a copy of sample.env as .env in local directory with appropriate credentials

#### Misc Notes
- grasp "username" is actually Telegram user ID or conversation ID to allow replies in conversation
- errors are logged to console, but not returned to user currently

#### Bot commands
`/report` issue report card in English
`/laporan` issue report card in Indonesian
`/start` issue initial text in Indonesian
