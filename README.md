# ⚙️ Educore Configuration Repository

This repository stores the centralized configuration for the **Educore Microservices Platform**. It is served by the Config Server to all microservices.

## 📂 Configuration Structure
| Service | File | Port | Description |
| :--- | :--- | :--- | :--- |
| **Student Service** | `student-service.yaml` | `8090` | Student management & PostgreSQL DB |
| **School Service** | `school-service.yaml` | `8091` | School profiles & PostgreSQL DB |
| **Service Registry** | `service-registry.yaml` | `8761` | Eureka Discovery Server |

## 🌿 Branching Strategy
* **`main`**: Production configurations.
* **`develop`**: Development configurations (Localhost).