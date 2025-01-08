# Vehicle Speed Monitoring System

## Overview
This system tracks vehicle speed continuously from ignition on to ignition off, using indexed data points. It is designed to monitor speed and detect overspeeding events by setting a speed threshold of **20 km/h**. When the vehicle speed exceeds this threshold, the system flags it as a **"red zone"** event, indicating an overspeeding occurrence.

## Objectives
- **Speed Tracking**: Monitor vehicle speed in real-time.
- **Threshold Detection**: Identify when the vehicle speed exceeds the predefined limit.
- **Event Logging**: Record and flag overspeeding events as "red zone" events for further analysis.

## Features
- **Real-Time Monitoring**:
  - Tracks vehicle speed continuously from the moment the ignition is turned on until it is turned off.
  
- **Threshold-Based Alerts**:
  - Flags instances where the vehicle speed exceeds **20 km/h**.

- **Red Zone Event Logging**:
  - Each overspeeding event is logged with relevant details such as time, index, and speed.

- **Data Indexing**:
  - Organizes speed data using indexes for efficient storage and retrieval.

## Technical Details
- **Speed Threshold**: 20 km/h
- **Monitoring Window**: From ignition-on to ignition-off.
- **Data Points**: Indexed speed data for structured tracking.

## How It Works
1. **Ignition On**:
   - The system begins tracking vehicle speed.

2. **Speed Monitoring**:
   - Continuously captures speed data indexed over time.

3. **Threshold Detection**:
   - Compares each speed data point against the threshold of **20 km/h**.

4. **Red Zone Event**:
   - If speed exceeds the threshold, a "red zone" event is logged.

5. **Ignition Off**:
   - Monitoring stops, and the session data is stored for analysis.

## Applications
- **Fleet Management**:
  - Identify and mitigate overspeeding behavior in real-time.

- **Safety Compliance**:
  - Ensure vehicles adhere to speed regulations.

- **Driver Performance Analysis**:
  - Monitor driving patterns and address unsafe practices.

## Future Enhancements
- Configurable speed thresholds for different vehicle types.
- Integration with GPS to log location-based overspeeding events.
- Real-time alerts for drivers during overspeeding instances.
- Data visualization tools for post-session analysis.

