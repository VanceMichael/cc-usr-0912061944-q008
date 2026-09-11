# 教师健康随访服务

Spring Boot 服务和 PostgreSQL 共同组成开发环境。HTTP 进程已提供健康检查，检查记录、提醒和审计模块位于 `src/main/java` 下扩展。

```bash
docker compose up --build -d
curl http://localhost:8080/health
docker compose down -v
```
