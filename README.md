# Project_Scripting
Intelligent Server Monitoring &amp; Self-Healing System is an automation project that continuously monitors server performance using a Bash-based monitoring engine and displays real-time analytics through a Flask-powered web dashboard. 

******Intelligent Server Monitoring & Self-Healing System******

This project is a simple but powerful system that continuously monitors a server’s health and reacts automatically when something goes wrong. It tracks CPU usage, memory usage, disk usage, and network latency using a shell script, and then displays this data in a live dashboard built with Flask and Chart.js.
The system also includes basic self-healing features such as killing high-CPU processes, detecting network failures, and cleaning up disk space when it gets too full. All activities and alerts are logged for later review.
This project is ideal for students learning Linux automation, DevOps fundamentals, or system monitoring — and it works great as a major academic project.

******What This System Does******

1.Monitors key system metrics in real time
2.stores logs with timestamps
3.Shows all metrics on a dashboard with live charts
4.Detects abnormal server behavior
5.Automatically performs corrective actions
6.Runs in the background using a Cron job


******Technologies Used******

1.Shell Script (Bash) – for monitoring and automation
2.Python (Flask) – for backend and API
3.HTML + Chart.js – for interactive graphs
4.Cron – for scheduled execution

**********Features Summary**********

1.CPU Monitoring: Detects high CPU usage and can terminate heavy processes
2.Memory Tracking: Logs RAM usage over time
3.Disk Monitoring: Warns and auto-cleans when disk is almost full
4.Network Latency Check: Identifies slow or dropped internet connections
5.Live Dashboard: Shows CPU, Memory, Disk, and Network performance trends
6.Logging System: All data and alerts stored for reference
7.Self-Healing: Automatically responds to issues

**********How It Works**********

1.A Bash script (monitor.sh) collects system statistics every minute.
2.The script writes the results to a log file.
3.A Flask application reads the log file and serves it as JSON.
4.A front-end dashboard (HTML + Chart.js) displays the data visually.
5.Cron automates the script so monitoring happens continuously.

**********Why This Project Is Useful**********

1.Helps understand real-world server monitoring concepts
2.Shows how automation can prevent system failures
3.Demonstrates both scripting
4.Useful for DevOps portfolios
5.Can be extended into a full observability tool

**********Future Improvements******

1.Email or Telegram alert notifications
2.Authentication for the dashboard
3.Multi-server monitoring support
4.Docker container deployment
5.Machine-learning based anomaly detection








