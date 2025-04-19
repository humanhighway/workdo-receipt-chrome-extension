# WorkDo Receipt Autofill Extension
This Chrome extension allows users to use the Google Gemini API to automatically analyze uploaded receipt images and fill the store name, amount, and date into their expense form.

## Features
WorkDo Receipt Autofill Extension is a Chrome extension designed to automate the process of filling in receipt information. Key features include:
- **Form Autofill**: Extracts data from uploaded receipt images and fills it directly into the corresponding fields of the WorkDo reimbursement system, improving efficiency and reducing manual errors.
- **PDF Invoice Recognition (not stable)**: Parses PDF electronic invoices that you upload on the WorkDo reimbursement page, quickly extracting invoice details.
- **Seamless Installation and Usage**: Works automatically on the WorkDo reimbursement page after installation, with no additional configuration required.
- Fills in the extracted data:
  - 小計 → 金額
  - 支出日期（起/迄）→ 日期
  - 細項說明 → 店家名稱

## Installation
1. Pack the extension (optional): on `chrome://extensions` click **Pack extension**, choose this project folder to generate a `.crx` file.
2. Drag and drop the generated `.crx` file onto the `chrome://extensions` page.
3. Confirm the installation.

## Usage
1. Upload a receipt image in your expense system.
2. Click the **Analyze** button on the uploaded image.
3. The extension will add a new entry and populate the store name, amount, and date.

## Configuration (Options)
1. Go to `chrome://extensions/` and find **WorkDO Receipt AutoFill**.
2. Click **Details** → **Extension options**.
3. In the options page (`options.html`), paste your Gemini API Key.
4. Click **Save** to apply.



