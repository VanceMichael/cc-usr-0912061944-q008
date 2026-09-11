# 快递路由账本

Java 服务和 PostgreSQL 共同组成开发环境。HTTP 进程已提供健康检查，扫描事件、账本和查询模块位于 `src/main/java` 下扩展。

```bash
docker compose up --build -d
curl http://localhost:8080/health
docker compose down -v
```
