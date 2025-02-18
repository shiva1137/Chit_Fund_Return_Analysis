# Chit Fund Return Analysis

## Project Overview:
This project provides an analysis tool for participants in a chit fund to assess their returns and compare them with bank FD (Fixed Deposit) interest over the same period. The tool allows users to input their contribution amounts, bidding data, and other relevant details, and then calculates the total benefits they receive from participating in the chit fund.

### Key Features:
- **Input Parameters**: Users can input the number of participants, contribution per member, FD interest rate, and Residue Amount for each round.
- **Calculated Outputs**: The tool calculates key metrics, including:
  - Amount Taken by the winning bidder
  - FD Interest returns based on the amount taken
  - Total benefits combining FD interest and chit fund profit
  - Discount per member (how much each person benefits from each bid)
  
### How It Works:
1. Users input the required values such as the number of members, contribution per member,Residue Amount and FD interest rate.
2. For each bidding round, users enter the Residue Amount.
3. The tool automatically calculates:
   - **Amount Taken** (amount the bidder receives)
   - **FD Interest Returns** (based on the Amount Taken and FD rate)
   - **Total Profit** from the chit fund’s discount distribution
4. The final analysis shows how the chit fund compares to a bank FD over time, helping participants determine when they would receive the maximum benefit from the chit.

### How to Use:
1. Clone or download this repository.
2. Open the `Chit_Fund_Analysis.xlsx` file in Excel.
3. Fill in the **input columns** (number of members, contribution per member, FD interest rate, and Residue Amount).
4. The tool will automatically calculate the **output columns** ( Amount taken, FD interest, etc.).
5. Review the analysis in the final columns to compare the benefits of participating in the chit fund versus investing in a bank FD.

### Example:
- **Number of Members**: `22`
- **Contribution per Member**: `₹20,000`
- **FD Interest Rate**: `8%`
- **Bidding Data**: User inputs various bidding rounds (e.g., ₹1,00,000, ₹60,000, etc.)
  Attaching Screenshot:
![image](https://github.com/user-attachments/assets/09b8b29d-596a-45fe-a215-885e616ca49f)


### Analysis Output:
The tool will output the **Amount Taken**, **FD Interest Amount Returns**, and **Total Benefits** for each bidding round, which will allow you to compare the benefits of chit fund participation to FD returns.

### Technologies Used:
- Excel
- Simple Interest Calculation for FD Returns

### Contributing:
Feel free to fork this repository and submit pull requests for enhancements or bug fixes.

### License:
This project is licensed under the MIT License.

### Contact:
For any inquiries, feel free to reach out to Shivaprakash at shivaprakash358158@gmail.com.

