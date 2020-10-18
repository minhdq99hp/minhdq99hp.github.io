# minhdq99hp.github.io

My name is Dang Quang Minh. I’m a senior student at Hanoi University of Science and Technology (HUST). My major is Information Communication and Technology (ICT).

In my opinion, writing blog is a good way to learn, especially for a developer. I’ve been writing this blog since the very first month of my university. The main purpose of this blog is to help me strengthening my knowledge. You can see that most of posts is about technology, programming, AI, hardware,… I also write posts about my opinion, my reviews and my experience.

I’ve categorized all posts into 4 categories:

- Technology
- Economics
- Art
- Thought

You can also find the post you want by using tags or search bar. Some posts that are not well edited will have their title start with ‘[Draft]’.

If you are recruiting or want to discuss with me about topics written in my blog, you can contact me on:

Facebook: fb.com/minhdq99hp
LinkedIn: linkedin.com/in/minhdq99hp
Email: minhdq99hp@gmail.com

## Setup
```
sudo apt-get install ruby-full build-essential zlib1g-dev
```

```
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

```
gem install jekyll bundler
```

Install additional gems:
```
bundle install
```

## Run
```
bundle exec jekyll serve
```

Build jekyll
```
bundle exec jekyll build --incremental
```
