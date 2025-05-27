# Phishing Indicators Report

## Step-by-Step Analysis

1. **Sender Address Check**
   - Sender: support@paypa1-secure.com
   - Spoofed domain: “paypa1” uses a digit “1” instead of the letter “l” to appear legitimate.

2. **Email Header Analysis**
   - Discrepancies found in SPF and DKIM entries using MxToolbox email header analyzer.
   - Return path does not match sending domain.

3. **Suspicious Links**
   - The button text “Verify Now” points to `http://bit.ly/fake-paypal-link`, which is a shortened, suspicious URL.

4. **Urgency or Threats**
   - Message uses threatening language: “Failure to act within 24 hours will result in permanent suspension”.

5. **Mismatched URLs**
   - Hovering reveals the real destination is different from what is implied by the button.

6. **Spelling/Grammar**
   - No major spelling errors, but tone is aggressive and unprofessional for a company like PayPal.

7. **Phishing Traits Summary**
   - Spoofed domain
   - Suspicious shortened URL
   - Urgent call-to-action
   - Generic greeting (“Dear Customer”)
   - Pressure tactic (account suspension)
   - No personal details or authentication

## Tools Used:
- VirusTotal for link scanning
- MxToolbox Header Analyzer
