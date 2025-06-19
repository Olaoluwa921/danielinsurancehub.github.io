
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daniel Insurance Hub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f7f9;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #003366;
            color: white;
            padding: 20px 0;
        }
        main {
            padding: 30px 20px;
        }
        .form-box {
            background: white;
            max-width: 400px;
            margin: 0 auto;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }
        label {
            display: block;
            margin: 15px 0 5px;
            text-align: left;
        }
        input[type="text"], input[type="tel"], select {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }
        .checkboxes label {
            display: block;
            text-align: left;
        }
        .submit-btn {
            background-color: #0077cc;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        .trust-section {
            margin-top: 40px;
            font-size: 16px;
        }
        .trust-section li {
            list-style: none;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Daniel Insurance Hub</h1>
        <p>Helping You Find the Best Insurance Plans – Fast, Free & Secure</p>
    </header>
    <main>
        <div class="form-box">
            <h2>Get Your Free Insurance Quote</h2>
            <form action="https://example.com/your-affiliate-link" method="GET">
                <div class="checkboxes">
                    <label><input type="checkbox" name="insurance_type" value="Medicare"> Medicare</label>
                    <label><input type="checkbox" name="insurance_type" value="Life"> Life Insurance</label>
                    <label><input type="checkbox" name="insurance_type" value="Health"> Health</label>
                    <label><input type="checkbox" name="insurance_type" value="Auto"> Auto</label>
                    <label><input type="checkbox" name="insurance_type" value="Other"> Other</label>
                </div>
                <label for="zipcode">Zip Code</label>
                <input type="text" id="zipcode" name="zipcode" required>

                <label for="phone">Phone Number</label>
                <input type="tel" id="phone" name="phone" required>

                <button class="submit-btn" type="submit">Get Free Quote Now</button>
            </form>
        </div>
        <div class="trust-section">
            <ul>
                <li>✔ 100% Free & No Obligation</li>
                <li>✔ Trusted By Thousands</li>
                <li>✔ Your Data is Safe With Us</li>
            </ul>
        </div>
    </main>
</body>
</html>
