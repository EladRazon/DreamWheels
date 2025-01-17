## 🚗 DreamWheels Management System  

## 📋 Project Overview  
**DreamWheels** is a **C-based vehicle management system** designed to streamline vehicle inventory tracking and facilitate vehicle purchases. The system offers:  
- Management of cars, motorcycles, and trucks.  
- Customer and order handling.  
- Invoice generation with support for installment payments.  

The project is structured using modular programming principles for clarity, scalability, and efficiency.  

## 📄 Project Description  
DreamWheels provides a comprehensive solution for vehicle inventory and purchase management, including:  
- Adding and managing vehicles across categories (cars, motorcycles, trucks).  
- Associating customers with purchased vehicles.  
- Generating detailed invoices with payment tracking, including installment options.  
- Searching and sorting vehicles based on various criteria (price, engine type, color, etc.).  

### Key Features:  
1. **Vehicle Management**:  
   - Add new vehicles to the system.  
   - Display vehicles categorized by type (car, motorcycle, truck).  
   - Print all vehicles currently in stock with detailed information.  

2. **Customer Management**:  
   - Add and manage customer details.  
   - Associate customers with their purchased vehicles.  

3. **Order Management**:  
   - Process vehicle purchases, including employee discount validation.  
   - Generate invoices for purchases, tracking payment status and delivery date.  

4. **Advanced Search and Sorting**:  
   - Search for vehicles using parameters like price range, engine type, and color.  
   - Sort vehicles based on selected criteria.  

5. **Invoice Management**:  
   - View and print all generated invoices.  
   - Track payment details for each purchase.  

## ⚙️ Program Structure  
The system is divided into modular components, each responsible for specific functionalities:  
- **`VehicleManager` Module**: Manages vehicle inventory and organizes data into arrays by type.  
- **`Customer` Module**: Stores customer details and their associated vehicles.  
- **`OrderManager` Module**: Handles vehicle purchases and employee discount verification.  
- **`Invoice` Module**: Manages invoice creation and payment tracking.  
- **`Main` Module**: Serves as the entry point with a menu-driven user interface.  
- **`Utility` Module**: Provides helper functions for validation and data handling.  

## 🏦 Key Functionalities  
1. **Add Vehicles**: Enter details like type, model, color, and price, and save them in the system.  
2. **Display Vehicles**: Print lists of vehicles categorized by type or all vehicles in stock.  
3. **Search Vehicles**: Find specific vehicles based on user-defined criteria.  
4. **Sort Vehicles**: Organize vehicle lists by selected attributes such as price or engine type.  
5. **Purchase Vehicles**: Guide users through the purchase process, including payment options and employee discounts.  
6. **Generate Invoices**: Create detailed invoices with payment breakdowns.  
7. **View Customers**: Display all customers and their purchase history.  

## 🚀 Installation  
1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/EladRazon/DreamWheels.git  
   ```  

2. **Navigate to the Project Directory**:  
   ```bash  
   cd DreamWheels  
   ```  

3. **Compile the Code**:  
   ```bash  
   gcc -o dreamwheels main.c *.c  
   ```  

4. **Run the Program**:  
   ```bash  
   ./dreamwheels  
   ```  

## 🚀 Usage Instructions  
The system provides an intuitive menu-driven interface with the following options:  
1. **Add Vehicle**: Add new vehicles to the system.  
2. **View Vehicles**: Display lists of vehicles categorized by type or all vehicles in stock.  
3. **Search Vehicles**: Find vehicles based on specific criteria.  
4. **Purchase Vehicle**: Complete vehicle purchases with invoice generation.  
5. **View Customers**: Display all customer details and their purchase history.  
6. **Exit**: Safely exit the system.  

## 📈 Future Expandability  
The system is designed for scalability, allowing for:  
- Integration with real-time inventory updates.  
- Advanced analytics for vehicle sales trends.  
- Expanded vehicle attributes and management capabilities.  

