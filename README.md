Code nằm bên nhánh Master 
chạy docker và compose: docker compose -f mySQL.yaml up -d --build
kết nối db: docker exec -it my-mysql mysql -uuser -ppass123 mydb
