# Demographic Data Analyzer

## Overview
This is a FreeCodeCamp Data Analysis with Python project that analyzes demographic data from the UCI Adult dataset. The project is set up as a learning exercise where students implement data analysis functions using pandas.

**Purpose**: Analyze demographic patterns in the adult income dataset to answer questions about race distribution, education levels, work hours, and income patterns across different demographics.

**Current State**: Environment fully configured and ready for development. The boilerplate code is in place with stub functions that need to be implemented.

**Key Features**:
- Data analysis using pandas
- Unit tests to verify implementations
- Console-based output showing analysis results

## Recent Changes
- 2025-09-22: Initial project setup completed
  - Installed Python 3.11 and pandas dependencies
  - Fixed numpy compatibility issues (downgraded to 1.24.3 for pandas 1.5.3)
  - Configured workflow to run the application
  - Verified all imports work correctly
  - Application runs successfully with expected test failures (functions not implemented yet)

## User Preferences
- Console-based application (no web frontend)
- Uses pandas for data analysis
- Follows FreeCodeCamp project structure and requirements

## Project Architecture

### File Structure
```
├── adult.data.csv              # UCI Adult dataset (32K+ records)
├── demographic_data_analyzer.py # Main analysis functions (stub implementations)
├── main.py                     # Entry point - runs analysis and tests
├── test_module.py              # Unit tests to verify implementations
├── requirements.txt            # Python dependencies
├── README.md                   # Project instructions
└── renovate.json              # Dependency management config
```

### Key Components
1. **Data Source**: CSV file with demographic data including age, education, occupation, income, etc.
2. **Analysis Module**: `demographic_data_analyzer.py` contains the main `calculate_demographic_data()` function
3. **Testing**: Automated unit tests check for correct calculations
4. **Entry Point**: `main.py` runs both analysis and tests

### Dependencies
- Python 3.11
- pandas==1.5.3 (for data manipulation)
- numpy==1.24.3 (compatible with pandas version)

### Workflow Configuration
- **Name**: Python App
- **Command**: `python main.py`
- **Output**: Console (shows analysis results and test outcomes)
- **Status**: Working correctly - runs analysis and tests

### Expected Development Flow
1. Students implement the stub functions in `demographic_data_analyzer.py`
2. Each function should return specific data analysis results
3. Unit tests will pass as functions are correctly implemented
4. Final output shows demographic insights from the dataset

### Architecture Decisions
- **Date**: 2025-09-22
- **Decision**: Use numpy 1.24.3 instead of latest version for pandas 1.5.3 compatibility
- **Reason**: Resolved binary incompatibility issues between numpy and pandas versions
- **Impact**: Stable pandas import and data processing functionality