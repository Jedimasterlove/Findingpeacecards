# Google Play Store Upload Checklist

## Pre-Upload Requirements

### ✅ Technical Setup
- [ ] Web app deployed and API URL updated in mobile app
- [ ] Production build created with `eas build --platform android --profile production`
- [ ] App tested on physical Android device
- [ ] All features working (decks, cards, accordion interface)

### ✅ App Assets Required
- [ ] **App Icon**: 1024x1024px PNG (mobile/assets/icon.png)
- [ ] **Feature Graphic**: 1024x500px PNG for store listing
- [ ] **Screenshots**: 2-8 phone screenshots (1080x1920px recommended)
- [ ] **Privacy Policy**: URL to hosted privacy policy

### ✅ Google Play Console Setup
- [ ] Google Play Console account created ($25 one-time fee)
- [ ] Developer account verified
- [ ] App created in console with basic details

## Upload Process Checklist

### Step 1: App Bundle Upload
- [ ] Navigate to Production > Releases
- [ ] Create new release
- [ ] Upload .aab file from EAS build
- [ ] Add release notes
- [ ] Set version code and version name

### Step 2: Store Listing
- [ ] **App name**: "Finding Peace - Conversation Cards"
- [ ] **Short description** (80 characters max)
- [ ] **Full description** (4000 characters max)
- [ ] **App icon** uploaded
- [ ] **Feature graphic** uploaded
- [ ] **Screenshots** uploaded (minimum 2)
- [ ] **App category**: Health & Fitness or Lifestyle
- [ ] **Tags**: therapy, relationships, communication

### Step 3: Content Rating
- [ ] Complete content rating questionnaire
- [ ] Submit for "Everyone" rating
- [ ] Confirm no inappropriate content

### Step 4: Data Safety
- [ ] Declare data collection practices
- [ ] Specify if app collects personal data
- [ ] Detail data sharing practices
- [ ] Privacy policy URL added

### Step 5: App Access
- [ ] Confirm app is accessible without special access
- [ ] No login required for basic functionality
- [ ] All features available to general users

### Step 6: Advertising
- [ ] Declare if app contains ads (likely "No")
- [ ] Specify ad content if applicable

## Final Review

### Before Submission
- [ ] All required fields completed (no red asterisks)
- [ ] Screenshots clearly show app functionality
- [ ] App description accurately represents features
- [ ] Privacy policy accessible and complete
- [ ] App tested on multiple Android devices

### After Submission
- [ ] Review submitted to Google
- [ ] Monitor email for review status updates
- [ ] Respond to any review feedback promptly
- [ ] Plan app marketing after approval

## Common Rejection Reasons to Avoid

- [ ] Missing privacy policy
- [ ] Misleading app description
- [ ] Low-quality screenshots
- [ ] App crashes or major bugs
- [ ] Incomplete store listing information
- [ ] Inappropriate content rating

## Post-Approval Tasks

- [ ] Download and test published app
- [ ] Monitor user reviews and ratings
- [ ] Plan app updates and improvements
- [ ] Consider iOS App Store submission

## Support Resources

- **Google Play Console Help**: https://support.google.com/googleplay/android-developer
- **EAS Build Docs**: https://docs.expo.dev/build/introduction/
- **App Store Optimization**: Research ASO best practices for therapy/wellness apps