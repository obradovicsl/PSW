# PSW


PSW is a project that uses **Angular** for the frontend and **ASP.NET** for the backend. This project uses **Git submodules** to keep the frontend and backend separated but integrated within the same repository.

## Repository Structure

The repository is organized with two main submodules:

1. **`frontend/`**: Contains the frontend application written in **Angular**.
2. **`backend/`**: Contains the backend application written in **ASP.NET**.

### How to Use the Project

1. **Cloning the Repository with Submodules**

   When cloning this repository, be sure to use the `--recursive` flag to clone the submodules as well:
   
   ```bash
   git clone --recursive https://github.com/obradovicsl/PSW.git
