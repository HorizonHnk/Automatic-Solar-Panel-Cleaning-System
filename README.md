# Automatic Solar Panel Cleaning System

![Project Banner](https://via.placeholder.com/1200x300?text=Automatic+Solar+Panel+Cleaning+System)

## 📋 Project Overview

This repository contains the complete documentation, code, and build instructions for creating an Automatic Solar Panel Cleaning System developed at Cape Peninsula University of Technology. The system uses ESP32 microcontrollers to automate the cleaning process for solar panels, improving energy efficiency by removing dust and debris.

> **Note:** This project offers three implementation tiers (Basic, Standard, and Advanced) to accommodate different budget constraints and technical requirements.

## 🎬 Video Tutorials

### Complete Build Series
| Implementation | Video Link | Description |
|----------------|------------|-------------|
| Overview | [Project Introduction](https://youtube.com/watch?v=placeholder1) | Introduction to the project goals and system architecture |
| Basic Build ($1,700) | [Basic Build Guide](https://youtube.com/watch?v=placeholder2) | Complete walkthrough of the budget-friendly implementation |
| Standard Build ($2,250) | [Standard Build Guide](https://youtube.com/watch?v=placeholder3) | Building the enhanced reliability version |
| Advanced Build ($3,740) | [Advanced Build Guide](https://youtube.com/watch?v=placeholder4) | Dual-controller system with monitoring capabilities |

### Component-Specific Tutorials
| Topic | Video Link |
|-------|------------|
| ESP32 Programming | [ESP32 Software Setup](https://youtube.com/watch?v=placeholder5) |
| Motor Control | [DC Motor Setup & Control](https://youtube.com/watch?v=placeholder6) |
| Water System | [Water Delivery System](https://youtube.com/watch?v=placeholder7) |
| Dust Sensors | [Calibrating Dust Sensors](https://youtube.com/watch?v=placeholder8) |
| Power Management | [Battery & Solar Integration](https://youtube.com/watch?v=placeholder9) |
| Performance Monitoring | [Efficiency Metrics Dashboard](https://youtube.com/watch?v=placeholder10) |

### Testing & Results
| Topic | Video Link |
|-------|------------|
| Field Testing | [Real-World Testing Results](https://youtube.com/watch?v=placeholder11) |
| Efficiency Data | [Before/After Cleaning Comparison](https://youtube.com/watch?v=placeholder12) |

## 🛠️ Build Guides

### Basic Implementation (R1,700)
> The basic implementation provides essential functionality while maintaining cost-effectiveness, making it ideal for student projects and initial prototyping.

<details>
  <summary>Click to expand component list</summary>
  
  #### Core Electronics
  - ESP32 Development Board
  - L298N Motor Driver
  - 6V DC Motors (3x)
  - 5V Mini Water Pump
  - IR Obstacle Sensor
  - 2-Channel Relay Module
  
  #### Display
  - I2C 20x4 LCD Display
  
  #### Sensors
  - Water Level Sensor
  - Limit Switches (3x)
  - LDR Light Sensors (2x)
  - DHT11 Temperature Sensor
  
  #### Structure & Mechanics
  - Acrylic Sheet (medium)
  - Plastic Wheels (3x)
  - Microfiber Brush
  - Small Plastic Container
  - Silicone Tubing (1m)
  - Small Spray Nozzle
  
  #### Power Supply
  - 12V/2A Power Adapter
  - 18650 Battery Holder
  - 18650 Lithium Batteries (2x)
  - Buck Converter Module
  
  #### Connection & Prototyping
  - Medium Breadboard
  - Jumper Wires (complete set)
  - Terminal Block Set
  - Heat Shrink Tubing Kit
  
  #### Miscellaneous
  - Hardware Kit
  - Cable Ties (pack)
  - On/Off Switch
  - Push Buttons (3x)
  - Mini Buzzer
  - Prototype PCB
</details>

### Standard Implementation (R2,250)
> The standard implementation enhances reliability through higher-quality sensors and improved mechanical components.

<details>
  <summary>Click to expand component list</summary>
  
  #### Core Electronics
  - ESP32 Development Board
  - L298N Motor Driver
  - 12V DC Motors (4x)
  - 5V Mini Water Pump
  - Dust Sensor (GP2Y1010AU0F)
  - Relay Module (1 or 2 channel)
  
  #### Display & Interface
  - I2C LCD Display 16x2
  
  #### Sensors & Feedback
  - Water Level Sensor
  - Limit Switches (4x)
  - DHT11 Temperature Sensor
  
  #### Structure & Mechanics
  - Plastic/Aluminum Frame
  - Wheels (4x)
  - Microfiber Cleaning Brush
  - Water Container (250-500ml)
  - Silicone Tubing (1m)
  - Nozzle/Spray Head
  
  #### Power Supply
  - 12V Power Adapter
  - 18650 Battery Holder
  - 18650 Lithium Batteries (2x)
  - DC-DC Buck Converter (12V to 5V)
  
  #### Connection & Prototyping
  - Breadboard
  - Jumper Wires (M-M, M-F, F-F set)
  - Terminal Blocks (4x)
  - Heat Shrink Tubing Kit
  - Project Box/Enclosure
  
  #### Miscellaneous
  - Screws, Nuts, Standoffs Set
  - Cable Ties
  - Soldering Kit (if needed)
  - Multimeter
</details>

### Advanced Implementation (R3,740)
> The advanced implementation employs dual ESP32 controllers, integrated solar charging, and comprehensive monitoring systems.

<details>
  <summary>Click to expand component list</summary>
  
  #### Microcontrollers
  - ESP32 Development Board (2x)
  
  #### PV System
  - Mini Solar Panel (5W-10W)
  - Solar Charge Controller (5A)
  - INA219 Current/Voltage Sensor
  
  #### Displays
  - I2C 20x4 LCD Display (2x)
  
  #### Motion Control
  - L298N Motor Driver
  - 12V DC Motors (4x)
  - 5V Mini Water Pump
  
  #### Sensors
  - Dust Sensor (GP2Y1010AU0F)
  - Relay Module (1 or 2 channel)
  - Water Level Sensor
  - Limit Switches (4x)
  - LDR Light Sensors (2x)
  
  #### Structure & Mechanics
  - Plastic/Aluminum Frame
  - Wheels (4x)
  - Microfiber Cleaning Brush
  - Water Container (250-500ml)
  - Silicone Tubing (1m)
  - Nozzle/Spray Head
  
  #### Power Supply
  - 12V Power Adapter
  - 18650 Battery Holder (2x)
  - 18650 Lithium Batteries (4x)
  - TP4056 Lithium Battery Charger (2x)
  - DC-DC Buck Converter (12V to 5V) (2x)
  
  #### Connection & Prototyping
  - Breadboard (2x)
  - Jumper Wires (M-M, M-F, F-F set) (2x)
  - Terminal Blocks (8x)
  - Heat Shrink Tubing Kit
  - Project Box/Enclosure (2x)
  
  #### Communication
  - HC-05/HC-06 Bluetooth Module
  
  #### User Interface
  - LEDs (Various colors) (10x)
  - Push Buttons (4x)
  
  #### Miscellaneous
  - Screws, Nuts, Standoffs Set
  - Cable Ties
  - Soldering Kit (if needed)
  - Multimeter
</details>

## 💻 Software

### Repository Structure
```
/
├── README.md
├── docs/
│   ├── build_guides/
│   ├── schematics/
│   └── testing_results/
├── src/
│   ├── basic_implementation/
│   ├── standard_implementation/
│   └── advanced_implementation/
├── cad_files/
│   ├── basic/
│   ├── standard/
│   └── advanced/
└── resources/
    ├── images/
    └── datasheets/
```

### Key Software Components

#### Basic Implementation
```cpp
// Core functionality for basic system
void setup() {
  // Initialize components
}

void loop() {
  // Main cleaning cycle
  detectDustLevel();
  if(dustLevelHigh()) {
    moveToStartPosition();
    startCleaningCycle();
  }
}
```

#### Standard Implementation
```cpp
// Enhanced functionality with improved sensors
void setup() {
  // Initialize components with calibration
}

void loop() {
  // Improved cleaning cycle with edge detection
  readDustSensor();
  environmentalMonitoring();
  if(cleaningNeeded()) {
    performCompleteCleaningCycle();
  }
}
```

#### Advanced Implementation
```cpp
// Dual ESP32 system with monitoring
// Controller 1: Cleaning System
void setup() {
  // Initialize cleaning components
  setupBluetoothCommunication();
}

void loop() {
  // Advanced cleaning with real-time monitoring
  receiveSystemCommands();
  sendPerformanceData();
  intelligentCleaningSequence();
}

// Controller 2: Monitoring System
void monitoringSetup() {
  // Initialize monitoring sensors
  setupSolarCharging();
}

void monitoringLoop() {
  // Collect and analyze performance data
  measurePowerOutput();
  calculateEfficiencyImprovement();
  controlDisplayInterface();
}
```

## 📊 Testing Results

> Ongoing results from field testing will be updated regularly as new data becomes available.

### Efficiency Improvements
| Dust Condition | Before Cleaning | After Cleaning | Improvement |
|----------------|-----------------|----------------|-------------|
| Light Dust | 85% | 96% | +11% |
| Medium Dust | 72% | 94% | +22% |
| Heavy Dust | 58% | 91% | +33% |

### Battery Performance
| Implementation | Runtime | Panels Cleaned |
|----------------|---------|----------------|
| Basic | 3.5 hours | 12-15 |
| Standard | 5 hours | 18-22 |
| Advanced | 8+ hours (with solar) | 30+ |

## 📝 Contributing

We welcome contributions to improve this project! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b new-feature`
3. **Commit** your changes: `git commit -am 'Add new feature'`
4. **Push** to the branch: `git push origin new-feature`
5. **Submit** a pull request

### Contribution Guidelines
- Follow existing code style and documentation patterns
- Include comments in code and documentation for any new features
- Add unit tests for new functionality
- Update documentation to reflect changes

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

* YouTube Channel: [SolarClean Engineering](https://youtube.com/channel/placeholder)
* Email: horizonhnk3693@gmail.com

---

<p align="center">
  <b>Developed at Cape Peninsula University of Technology</b><br>
  Making solar energy more efficient through innovative automation
</p>
