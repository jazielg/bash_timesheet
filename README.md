# Bash Timesheet

Control the projects/tasks you are doing with a simple terminal command.

## Installation

Download the file.

```bash
sudo chmod 777 timesheet # Execute permission
sudo mv timesheet /usr/bin # To execute "timesheet" command anywhere on terminal
```

## Usage

```bash
timesheet start "project name"
timesheet task "task description"
timesheet commit "commit url"
timesheet end "project name"
```
**Functions**
```bash
timesheet pause # To pause current project
timesheet continue # To continue current project
timesheet status # To see last 10 lines
timesheet reset # Erase last line
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
