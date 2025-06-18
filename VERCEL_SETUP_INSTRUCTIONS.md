
# Vercel Environment Variable Setup Instructions

## 1. Step-by-Step Vercel Environment Variable Setup
1. **Log in to Vercel**: Go to [Vercel Dashboard](https://vercel.com/dashboard) and log in with your account.
2. **Select Your Project**: Click on the project you want to configure.
3. **Navigate to Settings**: In the project dashboard, click on the 'Settings' tab.
4. **Environment Variables**: Scroll down to the 'Environment Variables' section.
5. **Add Variables**: Click 'Add' to create a new environment variable.
   - **Name**: Enter the variable name (e.g., `OPENAI_API_KEY`).
   - **Value**: Enter the variable value (e.g., your OpenAI API key).
   - **Environment**: Choose the environment (e.g., 'Production', 'Preview', 'Development').
6. **Save Changes**: Click 'Save' to apply the changes.

## 2. Local Development Setup Instructions
1. **Create .env.local File**: In your project root, create a file named `.env.local`.
2. **Add Variables**: Add your environment variables in the format `KEY=value`.
3. **Secure the File**: Ensure this file is listed in your `.gitignore` to prevent it from being committed to version control.

## 3. Security Best Practices
- **Keep Keys Secure**: Never expose API keys or sensitive information in client-side code.
- **Rotate Keys Regularly**: Change your API keys periodically to minimize security risks.
- **Use Environment Variables**: Always use environment variables to manage sensitive data.

## 4. Troubleshooting
- **Check Variable Names**: Ensure variable names in your code match those in Vercel.
- **Verify Deployment Logs**: Check Vercel deployment logs for any errors related to environment variables.
- **Test Locally**: Use local environment variables to test configurations before deploying.

## 5. Testing Environment Variables
- **Local Testing**: Use tools like `dotenv` to load environment variables locally.
- **Vercel Preview**: Deploy to a Vercel preview environment to test changes before going live.

## 6. GitHub Integration
1. **Connect Repository**: In Vercel, connect your GitHub repository to automate deployments.
2. **Environment Variables in GitHub**: Use GitHub Secrets to manage environment variables for CI/CD workflows.
3. **Automatic Deployments**: Enable automatic deployments for branches to streamline your development workflow.

## 7. Additional Resources
- [Vercel Documentation](https://vercel.com/docs)
- [Environment Variables in Vercel](https://vercel.com/docs/concepts/projects/environment-variables)
- [GitHub Secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets)
