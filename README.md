# GIT

echo "# commands" >> README.md /n
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Jaiminkapopara/{filename}.git
git push -u origin main

# Check Current Remote URL:
git remote -v

# Update Remote URL:
git remote set-url origin https://github.com/your-username/your-repo.git










# PRISMA

npm install @prisma/client @auth/prisma-adapter
npm i prisma --save-dev
npx prisma init --datasource-provider mongodb(or other )
npx prisma generate
npx prisma studio
