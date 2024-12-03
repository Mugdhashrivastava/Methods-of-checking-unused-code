# Methods-of-checking-unused-code


# Check Unused CSS and JS via DevTools  
1. **Right-click** on the page and select **Inspect**.  
2. Open the menu (three dots at the top-right of DevTools).  
3. Navigate to **Customize and Control DevTools > Run Command**.  
4. Type `Coverage` in the command palette and select it.  
5. In the **Coverage tab**, click **Start Recording**.  
6. Interact with the page to simulate usage.  
7. Click **Stop Recording**.

### Filter Unused Code:  
1. In the **Coverage tab**, use the dropdown above the results to filter:  
   - **CSS**: View only unused/used stylesheets.  
   - **JS**: View only unused/used scripts.  
   - **All**: View unused/used code for all resources.  
2. Click any resource to open it in the **Sources tab** and inspect unused parts.

### Pro Tip:  
Hover over the coverage bars to get exact usage percentages and focus on optimizing heavily unused resources.
