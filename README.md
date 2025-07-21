**Run the following scripts one by one:**

**1. Auto Mount Disk Script**  
```bash
bash <(curl -fsSL https://raw.githubusercontent.com/dipuyadav/huawei-scripts/refs/heads/main/auto-mount.sh)
```

**2. Node Exporter Install Script**  
```bash
bash <(curl -fsSL https://raw.githubusercontent.com/dipuyadav/huawei-scripts/refs/heads/main/node-exporter.sh)
```

**3. Disk Size Auto Increase Script**  
```bash
bash <(curl -fsSL https://raw.githubusercontent.com/dipuyadav/huawei-scripts/refs/heads/main/disk-size-auto-increase.sh)
```

**4. Docker Install Script**  
```bash
bash <(curl -fsSL https://raw.githubusercontent.com/dipuyadav/huawei-scripts/refs/heads/main/docker-install.sh)
```

---

**👉 To run all the above scripts in one single go:**  
```bash
bash <(curl -fsSL https://raw.githubusercontent.com/dipuyadav/huawei-scripts/refs/heads/main/auto-mount.sh) && \
bash <(curl -fsSL https://raw.githubusercontent.com/dipuyadav/huawei-scripts/refs/heads/main/node-exporter.sh) && \
bash <(curl -fsSL https://raw.githubusercontent.com/dipuyadav/huawei-scripts/refs/heads/main/disk-size-auto-increase.sh) && \
bash <(curl -fsSL https://raw.githubusercontent.com/dipuyadav/huawei-scripts/refs/heads/main/docker-install.sh)
```
> ⚠️ Make sure you have root/sudo privileges when running these.
