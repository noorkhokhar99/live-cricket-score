# Live Cricket Score Notifier

## About

Following a live cricket match while working on your computer could be challenging especially if you want to follow every important event like a batsman's milestone or a wicket. This project is designed just to solve this problem. You simply run the python application in the background and continue working on your computer. The python application notifies you based on the notification settings that you have configured.

### Notes

  1. This script was developed and tested only on Windows 10, Python v3.7.9.

  2. The live scores are fetched from http://static.cricinfo.com/rss/livescores.xml. The scores are generally fast and reliable from this source. But sometimes, other sources like cricbuzz might be faster by a ball or two.

### Built With

- [Python 3.7](https://www.python.org/downloads/release/python-379/)
- Python Modules:
  - [beautifulsoup4](https://pypi.org/project/beautifulsoup4/)
  - [plyer](https://pypi.org/project/plyer/)
  - [requests](https://pypi.org/project/requests/)

## Getting Started

### Prerequisites

1. Clone this repository by running the below command in a terminal:

   ```sh
   git clone https://github.com/shriram-m/cricket_score_notifier.git
   cd cricket_score_notifier
   ```

2. Install dependencies:

   ```sh
   pip install -r requirements.txt
   ```

### Usage

After installing the dependencies, all you need to do is to run the following command:

```sh
python cricket_score_notifier.py
```

You will get an interactive prompt where you'll specify the match number that you are interested in.

##### Figure 1. Terminal Output

![Figure 1](Screen%20Shot%201444-04-11%20at%2012.32.41%20PM.png)

After that, you can let the terminal run in the background and continue your work. The code will send you notifications on every configured event like after every over, wicket, innings, batsman milestone, batting team milestone, etc. See [Settings](#settings) section to customize your notification settings.

