# DNS (Domain Name System)
- DNS translates **domain names** (like `google.com`) into **IP addresses** (like `142.250.190.14`).

- It acts like the **phonebook of the internet**, helping devices find the correct server.

- Without DNS, we would need to remember **IP addresses** instead of names.

- Works in the background every time you visit a website, send email, or use an app.

## DNS hierarchy
### 1️⃣ **Root Level**: `.`
- The top of the DNS tree (invisible, but always there)
- Represented by a dot: `.`
- It points to **root name servers**

### 2️⃣ **Top-Level Domain (TLD)**: `.com`

The TLD is the part that comes **right after the domain name**, like `.com`, `.org`, or `.za`.

There are two main types:

---

#### 1. **ccTLD** (Country Code Top-Level Domain)
- Specific to a **country or region**
- Always **two letters**
- Examples:
  - `.za` → South Africa  
  - `.uk` → United Kingdom  
  - `.jp` → Japan  
  - `.us` → United States

---

#### 2. **gTLD** (Generic Top-Level Domain)
- Not tied to a country
- Used by **organizations, businesses, or general purposes**
- Examples:
  - `.com` → Commercial  
  - `.org` → Organizations  
  - `.net` → Networks  
  - `.edu` → Education  
  - `.za` → Government (SA-based)

  #### 3. **New gTLDs** (Modern Custom Domains)
- Recently added to expand naming options
- Examples:
  - `.tech`, `.xyz`, `.app`, `.blog`, `.security`

### 3️⃣ **Second-Level Domain**: `google`
- This is the main name you register (owned by Google)

### 4️⃣ **Subdomain / Hostname**: 
- `main`.google.com
