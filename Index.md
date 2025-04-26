# Data Management Plan

## Research Project Overview

This project investigates how publicly available vehicle sensor data can be used to detect and reduce risky driving behavior using machine learning techniques. The study focuses on recognizing unsafe patterns such as harsh braking, sudden acceleration, and drowsy or distracted driving. By analyzing large volumes of real-world sensor data, the project aims to support accident prevention systems, improve driver behavior, and contribute to the development of intelligent transportation technologies.

The data used is publicly available and will be downloaded from reliable sources such as Kaggle or university-hosted research portals. No new data collection involving human subjects will occur.

## Data Description

The dataset consists of observational, time-series data collected during real-world driving sessions using instrumented vehicles. It includes:

- **Sensor Data**: Vehicle speed, acceleration, braking force, steering angle, GPS coordinates.
- **Visual Data**: Dashcam video clips and still images (optional, depending on the dataset version).
- **Annotations**: Labels indicating driving events such as harsh braking, lane changes, or distraction.

**Data Formats**:
- Sensor and label data are provided in structured formats like CSV or JSON.
- Video files, if available, are typically in MP4 format.

**Data Collection**:
- Originally collected by research teams driving instrumented vehicles in traffic environments.
- Sensors and cameras automatically recorded driving behavior.
- Datasets were later cleaned, labeled, and made publicly accessible for research purposes.

**Data Volume**:
- Estimated between 30 and 50 GB, depending largely on the presence of video or image data.

## Roles and Responsibilities

As the graduate student leading this project, I (Raj Patel) am solely responsible for implementing and maintaining the Data Management Plan (DMP). Responsibilities include:

- **Data Acquisition**: Downloading the dataset from trusted sources and verifying data integrity.
- **Data Organization**: Sorting raw data, processed files, and results into clearly labeled, versioned folders.
- **Metadata Creation**: Writing documentation to describe folder contents, variable meanings, data processing steps, and tools used.
- **Quality Control**: Cleaning the dataset, identifying missing values, and documenting corrections.
- **Data Analysis**: Using Python libraries such as pandas, scikit-learn, and TensorFlow for machine learning model development, with version control through Git.
- **Access Control**: Limiting access to personal storage environments (Oregon State University’s OneDrive and encrypted local backups).

## Data Protection and Storage

Although the data is not sensitive, appropriate measures will be taken to ensure its security:

- **Primary Storage**: Oregon State University’s OneDrive cloud storage, backed up by OSU IT.
- **Secondary Backup**: Encrypted local hard drive and optionally a third backup on Google Drive.
- **Automation**: OneDrive handles continuous synchronization and version control; local backups will be updated weekly.

If project continuity becomes necessary (e.g., in the case of departure), all files, scripts, and documentation will be kept organized and updated to ensure a smooth handover.

Upon graduation, final copies of all research materials will be transferred to personal cloud storage and external drives to maintain long-term access.

## Compliance

There are no specific funder requirements (such as HIPAA or FERPA compliance) because the project uses publicly available data without new human subject involvement. Nevertheless, all data handling will adhere to Oregon State University’s data management policies and general best practices for research data security, organization, and reproducibility.

