## 🧾 **Docker Commands**

### 🔍 1. Search for an Image on Docker Hub  
```bash
docker search <image_name>
```

---

### ⬇️ 2. Pull Image from Docker Hub  
```bash
docker pull <image_name>
```

---

### 🖼️ 3. View All Docker Images  
```bash
docker images
```

---

### 🛠️ 4. Run MySQL Container with Custom Port and Password  
```bash
docker run -d -p <host_port>:<container_port> --name <container_name> -e MYSQL_ROOT_PASSWORD=<your_password> <image_name>
```

---

### 🏃 5. Check Running Containers  
```bash
docker ps
```

---

### 📦 6. Check All Containers (Including Stopped)  
```bash
docker ps -a
```

---

### 🔌 7. Access MySQL Inside the Container  
```bash
docker exec -it <container_name> mysql -u root -p
```

---

### 🚪 8. Exit MySQL Shell  
```sql
exit;
```

---

### ⛔ 9. Stop a Running Container  
```bash
docker stop <container_name>
```

---

### ▶️ 10. Start a Stopped Container  
```bash
docker start <container_name>
```

---

### 🧼 11. Remove a Container  
```bash
docker rm <container_name>
```

---

### 🗑️ 12. Remove an Image  
```bash
docker rmi <image_name_or_id>
```
