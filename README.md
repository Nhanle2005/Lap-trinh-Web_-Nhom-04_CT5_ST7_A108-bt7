Code nằm bên nhánh Master. 
Chạy docker và compose: docker compose -f mySQL.yaml up -d --build. 
Kết nối db: docker exec -it my-mysql mysql -uuser -ppass123 mydb
