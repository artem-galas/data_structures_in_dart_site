# Data Structures and Algorithms in Dart Static Site

Static site where you can find a brief information and highlighted code example from 
[Data Structures and Algorithms in Dart](https://github.com/artem-galas/data_structures_in_dart)

Site builds using [Jekyll](https://jekyllrb.com/) and hosted on github pages.

## Contributing
If you want to change any code example please go to [data_structures_in_dart](https://github.com/artem-galas/data_structures_in_dart) repo 

1. Clone this repo and its submodule
> NOTE: This repo has a git submodule, which affects how you clone it.

- Clone this repo and its submodule at the same, use the `--recurse-submodules` option:
```bash
git clone --recurse-submodules https://github.com/dart-lang/site-www.git
```
- If you've already cloned this repo without its submodule, then run this command from the repo root:
```bash
git submodule update --init --remote
```

2. Run Application:
- Install dependencies
```bash
bundle install
```
- run jekyll `bundle exec jekyll serve` OR just `jekyll serve`;
- open browser `http://localhost:4000/data_structures_in_dart_site/`


## TODO
- [ ] Add Copy for code samples
- [ ] Add output example after code sample
- [ ] Add images/schemas to articles (graph)
