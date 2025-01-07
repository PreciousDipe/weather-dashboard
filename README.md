# 30 Days DevOps Challenge - Weather Dashboard

Day 1: Building a weather data collection system using AWS S3 and OpenWeather API

## Technical Architecture
![Architecture Diagram](https://github.com/PreciousDipe/weather-dashboard/blob/main/src/weather-dashboard.drawio.png)


## Weather Dashboard
This application fetches real-time weather data for multiple cities, displays temperature (°F), humidity, and weather conditions and automatically stores weather data in AWS S3. It also Supports multiple cities tracking and Timestamps all data for historical tracking

## What I Learned
- Configuring an IAM user with proper permissions and setting up access keys for AWS CLI.
- Installing and configuring AWS CLI to manage cloud resources directly from VS Code.
- Managing environment variables securely by storing API keys in a `.env` file.
- Setting up Python virtual environments and installing dependencies with `requirements.txt`.
- Working with OpenWeatherMap API by creating an account and integrating its API key.
- Following Git workflows for forking, cloning, and managing projects in VS Code.
- Running Python scripts efficiently and integrating external APIs into projects.

## Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/PreciousDipe/weather-dashboard.git

2. Navigate to the project directory
   ```bash
   cd weather-dashboard

3. Install dependencies
   ```bash
   pip install -r requirements.txt

4. Configure environment variables in `.env`
   open_weather_api_key=your_api_key_here
   aws_bucket_name=your_bucket_name_here

5. Run the script
   ```bash
   python src/weather_dashboard.py

## Resources used for this project
- [AWS CLI Configuration](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- [OpenWeather](https://home.openweathermap.org/)
- [ShaeInTheCloud Youtube Video](https://youtu.be/A95XBJFOqjw?si=41zTO-4yrt-bn86U)
