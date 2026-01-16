# Project Setup Documentation  

## 1. Prerequisites  
- Node.js (v16 or above)  
- npm  

---

## 2. Backend Setup (`ecommerce-backend`)  

### Navigate to backend  
```bash
cd ecommerce-backend
```

### Install dependencies  
```bash
npm install
```

### Start the backend server  
```bash
npm start
```

Backend default URL:  
```
http://localhost:5000
```

---

## 3. Frontend Setup (`ecommerce-project`)  

### Navigate to frontend  
```bash
cd ecommerce-project
```

### Install dependencies  
```bash
npm install
```

### Start the frontend server  
```bash
npm run dev
```

Frontend default URL:  
```
http://localhost:3000
```

---

## 4. Running Both Together  
1. Start the backend first (`ecommerce-backend`).  
2. Then start the frontend (`ecommerce-project`).  
3. Open the frontend in the browser — it will communicate with the backend APIs.  

---

## 5. Build for Production  

### Backend build (if applicable)  
```bash
cd ecommerce-backend
npm run build
```

### Frontend build  
```bash
cd ecommerce-project
npm run build
```

The production build for frontend will be generated inside:  
```
ecommerce-project/build
```
