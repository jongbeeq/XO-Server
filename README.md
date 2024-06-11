## XO-SERVER
1.ดาวน์โหลดโปรเจ็คนี้ลงเครื่อง
2.Install Package
	CLI: pnpm install
3.Set Up Database
	3.1 เลือก Data Provider
		CLI: pnpm exec prisma init --datasource-provider [Data Provider]
		( Data Provider เช่น mysql)
	3.2 ใส่ข้อมูล DATABASE_URL ใน .env
        "[DataProvider]://[User]:[Password]@[Port]/[DatabaseName]"
 