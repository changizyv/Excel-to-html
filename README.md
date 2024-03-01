## Excel to HTML Table Converter by Simple Python code

The **Excel to HTML Table Converter** is a Python script that allows you to convert data from an Excel spreadsheet into an HTML table. Whether you're a developer, data analyst, or just someone who needs to display tabular data on a website, this tool can be helpful.

### How to Use

1. **Clone the Repository:**
    - First, clone this repository to your local machine using Git:
      ```
      git clone https://github.com/changizyv/Excel-to-html.git
      ```

2. **Install Dependencies:**
    - Make sure you have Python installed on your system.
    - Install the required Python packages (pandas and openpyxl) using pip:
      ```
      pip install pandas openpyxl
      ```

3. **Prepare Your Excel File:**
    - Create an Excel file (e.g., `source.xlsx`) containing the data you want to convert.
    - Ensure that the data is organized in rows and columns.

4. **Run the Script:**
    - Open a terminal or command prompt and navigate to the project directory.
    - Execute the script by running:
      ```
      python excel_to_html.py
      ```
    - The script will read the Excel file, generate an HTML table, and print the complete HTML code to the console.

5. **Customize the Output:**
    - Modify the `generate_header_html()` and `generate_footer_html()` functions in the script to customize the header and footer of your HTML page.
    - Adjust CSS styles within the `<style>` section to match your desired table appearance.

6. **Include Images or Logos:**
    - Place your logo image (e.g., `logo.png`) in the project directory.
    - Update the `<img>` tag in the header section to point to your logo file.

7. **Use the Generated HTML:**
    - Copy the entire HTML output from the console.
    - Paste it into your web page or content management system (CMS) where you want to display the table.
    - Adjust the layout, fonts, and colors as needed.

### Example

Suppose you have an Excel file with sales data, and you want to display it on your website. This tool will convert the data into a clean HTML table that you can easily integrate into your site.

Feel free to explore the code, make enhancements, and adapt it to your specific requirements. Happy coding! 🚀

---

*Powered by Hashem Changizy*

[GitHub Repository](https://github.com/changizyv/Excel-to-html)
