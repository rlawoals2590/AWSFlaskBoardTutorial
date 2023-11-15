# AWSFlaskBoardTutorial

This repository contains source code and resources for building and hosting flask a board website on AWS, designed for

## Project setup

```
pip install -r requirements.txt
```

### Flask Run (Windows)

```
set FLASK_APP=main

set FLASK_DEBUG=true
```

### Flask Run (MacOS)

```
export FLASK_APP=main

export FLASK_DEBUG=true
```

### Database init

```
flask db init
```

### Database migrate

```
flask db migrate
```

### Database upgrade

```
flask db upgrade
```

### Flask server start

```
flask run
```
