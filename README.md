# wec-ruby1011
## 実行ログ
fukuzaki93:~/workspace $ mkdir wec-ruby1011
fukuzaki93:~/workspace $ cd wec-ruby1011/
fukuzaki93:~/workspace/wec-ruby1011 $ echo "# wec-ruby1011" >> README.md
fukuzaki93:~/workspace/wec-ruby1011 $ git init
Initialized empty Git repository in /home/ubuntu/workspace/wec-ruby1011/.git/
fukuzaki93:~/workspace/wec-ruby1011 (master) $ git add README.md
fukuzaki93:~/workspace/wec-ruby1011 (master) $ git commit -m "first commit"
[master (root-commit) c8391a2] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
fukuzaki93:~/workspace/wec-ruby1011 (master) $ git remote add origin git@github.com:FuKuZaKi-93/wec-ruby1011.git
fukuzaki93:~/workspace/wec-ruby1011 (master) $ git push -u origin master
Warning: Permanently added 'github.com,192.30.253.112' (RSA) to the list of known hosts.
Counting objects: 3, done.
Writing objects: 100% (3/3), 235 bytes | 235.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:FuKuZaKi-93/wec-ruby1011.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
fukuzaki93:~/workspace/wec-ruby1011 (master) $ git status
On branch master
Your branch is up-to-date with 'origin/master'.

nothing to commit, working tree clean
fukuzaki93:~/workspace/wec-ruby1011 (master) $ cd
fukuzaki93:~ $ sudo gem install pry
Fetching: coderay-1.1.2.gem (100%)
Successfully installed coderay-1.1.2
Fetching: method_source-0.9.0.gem (100%)
Successfully installed method_source-0.9.0
Fetching: pry-0.11.2.gem (100%)
Successfully installed pry-0.11.2
3 gems installed
fukuzaki93:~ $ pry
[1] pry(main)> exit
fukuzaki93:~ $ sudo gem install bundler
Fetching: bundler-1.15.4.gem (100%)
Successfully installed bundler-1.15.4
1 gem installed
fukuzaki93:~ $ cd workspace/
fukuzaki93:~/workspace $ cd wec-ruby1011/
fukuzaki93:~/workspace/wec-ruby1011 (master) $ bundle init
Writing new Gemfile to /home/ubuntu/workspace/wec-ruby1011/Gemfile
fukuzaki93:~/workspace/wec-ruby1011 (master) $ bundle install
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
fukuzaki93:~/workspace/wec-ruby1011 (master) $ ruby nokogiri.rb 
"神戸電子専門学校｜IT・Web・グラフィックデザイン・ゲームクリエイターに 強い専門学校"
fukuzaki93:~/workspace/wec-ruby1011 (master) $ 