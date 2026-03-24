# Legacy-to-Cloud Migration Showcase
> Demonstrating pragmatic migration patterns from monolithic architecture to cloud-native microservices

## Project Goal
This project showcases a realistic migration journey from a traditional monolithic application 
to a modern cloud-native microservices architecture, emphasizing:
- **Zero-Downtime Migration** using Strangler-Fig Pattern
- **Practical Migration Patterns** (not just theory)
- **Real-World Trade-offs** (senior-level decision making)

## Architecture
- **Phase 1**: Monolithic Application (simulated legacy system)
- **Phase 2**: Service extraction (User, Product, Order services)
- **Phase 3**: Cloud deployment (Docker + Kubernetes)
- **Phase 4**: Observability & Production-readiness

## Tech Stack
- Backend: Python (Flask/FastAPI)
- Containers: Docker, Docker Compose
- Orchestration: Kubernetes
- IaC: Terraform
- Database: PostgreSQL