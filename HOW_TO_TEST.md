# HOW TO TEST

## Opening the Website
1. Navigate to the `agile-website-main` folder
2. Double-click `index.html` OR right-click → Open with → Your Browser (Chrome, Firefox, Safari, etc.)

## What Should Happen

### ✅ Landing Page (Home)
- You should see the Fact Hub homepage
- Navigation shows: Features, Pricing, Reviews, Log in, Sign up buttons
- Everything should be visible and clickable

### ✅ Pricing Page (Without Login)
1. Click "Pricing" in the navigation
2. You should see 3 plans: Free ($0), Pro ($9), Team ($29)
3. Each plan shows features and a "Subscribe" button
4. **Click any "Subscribe" button** → Login modal should appear
5. You'll see message: "Please log in or sign up to subscribe to a plan."

### ✅ Login & Subscribe
1. In the login modal, enter any email (e.g., test@test.com)
2. Enter any password (e.g., password123)
3. Click "Log in" or "Sign up"
4. You'll be logged in!
5. Top right now shows: Plan badge (FREE) + Profile icon (👤 or your initials)
6. Go back to Pricing page
7. Now you can click "Subscribe" and it will work!

### ✅ Profile Page (After Login)
1. Click the profile icon (top right)
2. You should see:
   - Your avatar with initials
   - Profile information (name, email, bio - all editable)
   - Current subscription plan
   - Verification usage
   - Preferences (toggles for notifications, auto-check)
   - Recent activity
   - Logout and Delete Account buttons

### ✅ Account Deletion
1. Go to profile page (while logged in)
2. Scroll to bottom "Danger Zone"
3. Click "Delete Account"
4. Confirm TWICE
5. Account deleted, you're logged out, back to homepage

## Troubleshooting

**If nothing appears:**
- Open browser console (F12) and check for errors
- Make sure all 3 files (index.html, app.js, styles.css) are in the same folder

**If JavaScript doesn't work:**
- Check that `app.js` is in the same folder as `index.html`
- Try a different browser (Chrome recommended)

**If styling looks broken:**
- Check that `styles.css` is in the same folder as `index.html`
