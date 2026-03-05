## prom-robotics

`prom-robotics` is the GitHub organization for the commercial robotics unit of Innopolis University — **Отдел разработки технологических решений** (Department for Technological Solutions Development).
The organization hosts software used in industrial and commercial robotics projects.

### Department

- **Department name**: Отдел разработки технологических решений  
- **Head of department**: **Albert Demian** (`a.demian@innopolis.university`)

The department develops full‑stack technological solutions, from algorithms and system integration to backend and frontend components.

### Projects

All project repositories in `prom-robotics` are **private** and intended **only for employees of Отдел разработки технологических решений**.

- **DMD Project** - fixing defected steel matrices using Direct Metal Disposition technology:
  - **[dmd-api](https://github.com/prom-robotics/dmd-api)** (Python)
    DMD Backend providing services and APIs for data processing and integration with robotic systems.
  
  - **[dmd-frontend](https://github.com/prom-robotics/dmd-frontend)** (TypeScript)  
    DMD Web interface used to configure, monitor, and operate DMD‑based solutions.
  
  - **[dmd-algorithms](https://github.com/prom-robotics/dmd-algorithms)** (C++) ⚠️ Currently not used, archived.  
    Performance‑critical algorithmic components used across DMD services.

  - **[dmd-md](https://github.com/prom-robotics/dmd-md)**
    Internal documentation, specifications, and supporting materials for the DMD project.

  - **[dmd-ros](https://github.com/prom-robotics/dmd-ros)** 🚧 WIP. Will be used in future.
    ROS-related components and integration for DMD robotic cells.

  - **[kawasaki-communication-setup](https://github.com/prom-robotics/kawasaki-communication-setup)** (AngelScript)  
    `.as` script running on Kawasaki robots that accepts commands via TCP for low-level robot communication. Also there is instruction to run K-ROSET in Releases.

- **Welding Project** - Automatic and semi-automatic welding using manipulators.
  
  - **[welding-demo](https://github.com/prom-robotics/welding-demo)** (JavaScript)
    Demo and visualization tooling for validating and presenting `welding` capabilities.

  - **[welding](https://github.com/prom-robotics/welding)** (Python)
    A Python package for ICP between STEP models and point‑cloud scans for industrial welding and alignment tasks. Also will include other algorithms needed for welding.

  - **[welding-cv](https://github.com/prom-robotics/welding-cv)** 🚧 WIP. Will be used in future.
    CV module for camera scanning and ICP registration used in welding workflows.

  - **[calibration-system](https://github.com/prom-robotics/calibration-system)** (Python)  ⚠️ Currently not used, archived.
    Eye-on-hand calibration system for robot–camera setups.

### Access and Permissions

Access to `prom-robotics` repositories is restricted: Only employees of **Отдел разработки технологических решений** can get access.
In order to get access, contact one of the following within the department: **Artem Bulgakov** or **Ruslan Belkov**, they handle repository and team permissions inside the `prom-robotics` organization.
