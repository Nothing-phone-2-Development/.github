# Development for Nothing Phone (2) (Pong)

Welcome to the official development repository for **Nothing Phone (2)**, also known as **Pong**. This organization contains all the essential repositories and resources required to build **LineageOS** and other **AOSP-based ROMs** for the **Nothing Phone (2)**. <img src="https://github.com/user-attachments/assets/43edb56d-fe3e-4b9b-9211-3ab3d584b1d3" alt="BA_ALAK_190 1001" align="right" width="380" height="200" />

This project provides the necessary tools, configurations, and instructions to help you get started with building custom ROMs for the Nothing Phone (2).

To initialize your local repository using the official **LineageOS** trees, follow these steps:

### 1. Initialize the Repository
Run the following command to initialize your repository:

```bash
repo init -u git@github.com:Nothing-phone-2-Development/android.git -b lineage-22.1 --git-lfs
```

This command will set up the local environment with the correct branches and configurations for building the **LineageOS** ROM.

### 2. Sync the Repository
Next, synchronize your repository with the remote server:

```bash
repo sync
```

This will download all the necessary sources to build the ROM.

## Building LineageOS for Nothing Phone (2)

### 1. Set Up the Build Environment

To set up the environment, source the build script:

```bash
. build/envsetup.sh
```

### 2. Choose a Target Device

For **Nothing Phone (2)** (codename **Pong**), select the appropriate build target:

```bash
lunch lineage_Pong-ap4a-userdebug
```

### 3. Build the ROM

Finally, you can start the build process:

```bash
m bacon
```

This command will begin building the **LineageOS** ROM for your device. The process may take some time depending on your system's capabilities.

## Contributing

We welcome contributions from the community! If you'd like to contribute or make improvements, feel free to open a pull request.

---

### Key Points:
- This guide helps developers set up the environment and build custom ROMs for **Nothing Phone (2)**.
- **LineageOS** 22.1 is the default branch for building.
- You can easily set up the environment and start building by following a few simple commands.
