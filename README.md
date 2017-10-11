# wec-ruby1011
## 実行ログ

kogadoom:~/workspace $ wec-ruby1011
bash: wec-ruby1011: command not found
kogadoom:~/workspace $ mkdir wec-ruby1011
kogadoom:~/workspace $ cd wec-ruby1011
kogadoom:~/workspace/wec-ruby1011 $ echo "# wec-ruby1011" >> README.md
kogadoom:~/workspace/wec-ruby1011 $ git init
Initialized empty Git repository in /home/ubuntu/workspace/wec-ruby1011/.git/
kogadoom:~/workspace/wec-ruby1011 (master) $ git add README.md
kogadoom:~/workspace/wec-ruby1011 (master) $ git commit -m "first commit"
[master (root-commit) ffd3b21] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
kogadoom:~/workspace/wec-ruby1011 (master) $ git remote add origin https://github.com/kogatoshi/wec-ruby1011.git
kogadoom:~/workspace/wec-ruby1011 (master) $ git push -u origin master
Username for 'https://github.com': kogatoshi
Password for 'https://kogatoshi@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 235 bytes | 235.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/kogatoshi/wec-ruby1011.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
kogadoom:~/workspace/wec-ruby1011 (master) $ git status
On branch master
Your branch is up-to-date with 'origin/master'.

nothing to commit, working tree clean
kogadoom:~/workspace/wec-ruby1011 (master) $ sudo gem install pry
Fetching: coderay-1.1.2.gem (100%)
Successfully installed coderay-1.1.2
Fetching: method_source-0.9.0.gem (100%)
Successfully installed method_source-0.9.0
Fetching: pry-0.11.1.gem (100%)
Successfully installed pry-0.11.1
3 gems installed
kogadoom:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> 10.times do
[1] pry(main)*   puts i
[1] pry(main)*   
[1] pry(main)> 
kogadoom:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> quit
kogadoom:~/workspace/wec-ruby1011 (master) $ pry
[1] pry(main)> sudo gem install bundler
NameError: undefined local variable or method `bundler' for main:Object
from (pry):1:in `__pry__'
[2] pry(main)> quit
kogadoom:~/workspace/wec-ruby1011 (master) $ sudo gem install pry
Successfully installed pry-0.11.1
1 gem installed
kogadoom:~/workspace/wec-ruby1011 (master) $ sudo gem install bundler
kogadoom:~/workspace/wec-ruby1011 (master) $ sudo gem install bundler
Fetching: bundler-1.15.4.gem (100%)
Successfully installed bundler-1.15.4
1 gem installedkogadoom:~/workspace/wec-ruby1011 (master) $ bundle init
Writing new Gemfile to /home/ubuntu/workspace/wec-ruby1011/Gemfile
kogadoom:~/workspace/wec-ruby1011 (master) $ bundle install
The Gemfile specifies no dependencies
Resolving dependencies...
Bundle complete! 0 Gemfile dependencies, 1 gem now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
kogadoom:~/workspace/wec-ruby1011 (master) $ bundle install
The Gemfile specifies no dependencies
Bundle complete! 0 Gemfile dependencies, 1 gem now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
kogadoom:~/workspace/wec-ruby1011 (master) $ bundle init
Gemfile already exists at /home/ubuntu/workspace/wec-ruby1011/Gemfile
kogadoom:~/workspace/wec-ruby1011 (master) $ bundle install
The Gemfile specifies no dependencies
Bundle complete! 0 Gemfile dependencies, 1 gem now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
kogadoom:~/workspace/wec-ruby1011 (master) $ bundle install
Fetching gem metadata from https://rubygems.org/.............
Fetching version metadata from https://rubygems.org/.
Resolving dependencies...
Using bundler 1.15.4
Fetching mini_portile2 2.3.0
Installing mini_portile2 2.3.0
Fetching nokogiri 1.8.1
Installing nokogiri 1.8.1 with native extensions
Bundle complete! 1 Gemfile dependency, 3 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
kogadoom:~/workspace/wec-ruby1011 (master) $  ruby nokogiri.rb
"神戸電子専門学校｜IT・Web・グラフィックデザイン・ゲームクリエイターに強い専門学校"
kogadoom:~/workspace/wec-ruby1011 (master) $  git add *
kogadoom:~/workspace/wec-ruby1011 (master) $ git commit -m '10/11 実行ログ'
[master 3e9c8c5] 10/11 実行ログ
 3 files changed, 33 insertions(+)
 create mode 100644 Gemfile
 create mode 100644 Gemfile.lock
 create mode 100644 nokogiri.rb
kogadoom:~/workspace/wec-ruby1011 (master) $ git push
Username for 'https://github.com': kogatoshi
Password for 'https://kogatoshi@github.com': 
Counting objects: 5, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 773 bytes | 773.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/kogatoshi/wec-ruby1011.git
   ffd3b21..3e9c8c5  master -> master
kogadoom:~/workspace/wec-ruby1011 (master) $ 