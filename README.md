# 4-Month .NET + React Cloud-Native Learning Roadmap

## Month 1 – Backend & Microservices Foundation
- [ ] **Week 1: .NET Core API Refresher**
  - [ ] Review ASP.NET Core Web API fundamentals
  - [ ] Implement Products CRUD API with EF Core + SQL Server
  - [ ] Apply Repository + Unit of Work pattern
- [ ] **Week 2: Microservices Architecture Basics**
  - [ ] Learn monolith vs microservices
  - [ ] Implement gRPC between Products & Orders service
  - [ ] Add API Gateway (Ocelot/YARP)
- [ ] **Week 3: Messaging & Event-Driven Architecture**
  - [ ] Learn Kafka fundamentals (topics, producers, consumers)
  - [ ] Implement OrderPlaced → Notifications event flow
- [ ] **Week 4: Distributed Caching & NoSQL**
  - [ ] Learn Redis caching (cache-aside, pub/sub)
  - [ ] Add Redis caching to Products service
  - [ ] Learn MongoDB basics & create Reviews service

---

## Month 2 – Containers & Orchestration
- [ ] **Week 5: Docker**
  - [ ] Learn Docker multi-stage builds & image optimization
  - [ ] Dockerize all microservices
  - [ ] Run services with Docker Compose
- [ ] **Week 6: Kubernetes Basics (Local)**
  - [ ] Learn pods, deployments, services
  - [ ] Deploy microservices to Minikube/Docker Desktop
- [ ] **Week 7: Kubernetes Advanced (Local)**
  - [ ] Learn HPA (autoscaling), rolling updates, probes
  - [ ] Implement scaling & zero-downtime updates
- [ ] **Week 8: CI/CD**
  - [ ] Learn Azure DevOps pipelines
  - [ ] Create multi-stage build → test → deploy pipeline
  - [ ] Push Docker images to Docker Hub

---

## Month 3 – Cloud, IaC, and Monitoring
- [ ] **Week 9: Azure Fundamentals**
  - [ ] Create Azure Free Tier account
  - [ ] Learn AKS, ACR, networking basics
- [ ] **Week 10: Deploying to AKS**
  - [ ] Push images to ACR
  - [ ] Deploy to AKS using Helm
- [ ] **Week 11: Terraform**
  - [ ] Learn Terraform basics
  - [ ] Provision AKS + ACR with Terraform scripts
- [ ] **Week 12: Monitoring & Logging**
  - [ ] Learn ELK basics & set up logging
  - [ ] Add Prometheus & Grafana dashboards
  - [ ] Implement OpenTelemetry tracing

---

## Month 4 – Frontend Integration & Final Project
- [ ] **Week 13: React Fundamentals**
  - [ ] Learn components, hooks, props, state
  - [ ] Build product listing & order creation pages
- [ ] **Week 14: React Advanced**
  - [ ] Learn state management (Redux/Zustand)
  - [ ] Add cart & real-time notifications
- [ ] **Week 15: Final Integration**
  - [ ] Host frontend on Azure Static Web Apps
  - [ ] Test end-to-end flow
- [ ] **Week 16: Polish & Portfolio**
  - [ ] Write README with architecture diagram
  - [ ] Record demo video
  - [ ] Push final code to GitHub
