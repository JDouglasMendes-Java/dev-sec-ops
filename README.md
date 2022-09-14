# dev-sec-ops

## Port

| Microservice        | External    | Internal |
| ------------------- | ----------- |----------|
| db-postgres         | 15432       | 5432     |
| client-pgadmin      | 16543       | 80       |
| ------------------- | ----------- | -------- |
| Prometheus          | 4000        | 4000     |
| Grafana             | 3000        | 3000     |
| ------------------- | ----------- | -------- |
| Service Register    | 9090        |  9090    |
| Gateway             | 9091        |  9091    |
| Products            | 9092        |  9092    |
| Catalog             | 9093        |  9093    |
| Order               | 9094        |  9094    |
| Payments            | 9095        |  9095    |

## External host

- Postgresql: <http://localhost:16543/login?next=%2F>
- Grafana: <http://localhost:3000/>
- Eureka: <http://localhost:9090/>
- Product: <http://localhost:9091/ms-product/health>
  