# Sweep AI Troubleshooting

## Issue: Sweep AI not responding to GitHub issues

### Attempted Solutions:
1. ✅ Created `.sweep/config.yml` configuration file
2. ✅ Created `.github/workflows/sweep.yml` GitHub Actions workflow
3. ✅ Verified Sweep AI GitHub App installation
4. ✅ Confirmed GitHub Actions permissions are enabled
5. ✅ Used correct issue format with "Sweep:" prefix
6. ✅ Tried different Sweep AI versions (v1.1.6 and @main)
7. ✅ Simplified configuration to minimal settings
8. ✅ Added explicit permissions to workflow

### Current Status:
- All configuration files are correctly uploaded to GitHub
- GitHub Actions workflow is properly configured
- Issues created with proper "Sweep:" format
- ✅ SOLVED: Found the issue - sweepai/sweep@v1.1.6 version doesn't exist
- Fixed by changing to sweepai/sweep@main

### Next Steps to Try:
1. Check if Sweep AI service is operational
2. Verify GitHub App has all required permissions
3. Try creating issue with different format
4. Check GitHub Actions logs for any errors

### Commands Used:
```bash
# Commit changes
git add .
git commit -m "Update Sweep AI configuration"
git push origin main
```
