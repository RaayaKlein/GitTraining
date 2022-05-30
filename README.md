# Git training

## third change

# configure user: 

```
git config --global user.email "you@example.com"

git config --global user.name "Your Name"
```

### …or create a new repository on the command line

```
echo "# GitTraining" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/RaayaKlein/GitTraining.git
git push -u origin main
```
### …or push an existing repository from the command line
```
git remote add origin https://github.com/RaayaKlein/GitTraining.git
git branch -M main
git push -u origin main
```
