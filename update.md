## How to deploy

First clone the repository and update!

```console
git clone git@gitnahid:mohammad-nahid-hossain/academic-kickstart.git nahid

cd nahid

git submodule update --init --recursive
```

Then delete the public folder if exists! And after that add the submodule by typing the following in the terminal.

```console
git submodule add -f -b master git@gitnahid:mohammad-nahid-hossain/mohammad-nahid-hossain.github.io.git public
```

Now lets push those codes into the repository.

```console
git add .
git commit -m "message"
git push -u origin master
```

We will generate the website now and then push the website into the repository.

```conosole
hugo
cd public
git add .
git commit -m "message"
git push -u origin master
cd ..
```

Now, its done!

