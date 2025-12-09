# Bulk Requisition Creation Tool

A full-stack **Node.js + TypeScript + React** application that enables business users to create large batches of requisitions through CSV upload. Designed for high-volume workflows, the tool validates input, previews generated entries, and processes records in efficient batches with error handling and rollback support.

---

## 🚀 Features

### ✅ Bulk CSV Upload
- Drag-and-drop or file selector input  
- Parses CSV into structured requisition objects  
- Validates required fields and data formats

### ✅ Preview & Validation
- Shows users all parsed items before committing  
- Highlights invalid rows with error messages  
- Allows editing individual entries prior to submission

### ✅ Efficient Batch Processing
- Sends records to the server in optimized batches  
- Supports MongoDB transactions for consistency  
- Provides progress tracking during large imports

### ✅ Error Recovery & Rollback
- Automatically rolls back failed batches  
- Detailed logs for processing errors  
- Ensures data integrity even at scale

### ✅ Modern UI
- Built with React + TypeScript  
- Clean Material UI interface  
- Real-time feedback during uploading and processing  

---

## 📦 Tech Stack

### **Backend**
- Node.js  
- TypeScript  
- Express.js  
- MongoDB + Mongoose  
- CSV parsing (PapaParse / Fast-CSV)

### **Frontend**
- React  
- TypeScript  
- Material UI  
- Axios  

---

## 📁 Project Structure

### Backend
