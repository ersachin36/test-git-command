# Git Setup and Basic Workflow Commands

## Initial Setup

1. Create accounts:
   - Github: Visit github.com and sign up
   - Gitlab: Visit gitlab.com and sign up
   - Bitbucket: Visit bitbucket.org and sign up

2. Create new repository:
   - Through web interface of chosen platform
   - Or use existing repository

3. Generate SSH key:
   ```bash
   ssh-keygen -t ed25519 -C "your_email@example.com"
   ```

4. Add SSH key to account:
   ```bash
   # Copy SSH key
   cat ~/.ssh/id_ed25519.pub
   # Add to platform's SSH settings
   ```

5. Initialize git repository:
   ```bash
   git init
   ```

6. Add remote URL:
   ```bash
   git remote add origin git@github.com:username/repository.git
   ```

## Basic Workflow Commands

7. Make and stage changes:
   ```bash
   # Make your changes to files
   
   # Stage changes
   git add .  # Add all changes
   # OR
   git add <filename>  # Add specific file
   ```

8. Commit changes:
   ```bash
   git commit -m "Your commit message"
   ```

9. Push changes:
   ```bash
   git push origin main
   ```

## Repeat Development Cycle

10. Make and push new changes:
    ```bash
    # Make changes to files
    git add .
    git commit -m "New changes"
    git push origin main
    ```

## Merging

11. Merge branches:
    ```bash
    # Switch to target branch
    git checkout main
    
    # Merge source branch
    git merge <source-branch>
    ```
