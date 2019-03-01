# c_tutorial
Udemy講座のC言語練習とBazelとgitとgithubに慣れるためのリポジトリ。

## Usage
```bash
# bazel で build する.
bazel build //main:hello-world
> INFO: Analysed target //main:hello-world (3 packages loaded, 25 targets configured).
> INFO: Found 1 target...
> Target //main:hello-world up-to-date:
>   bazel-bin/main/hello-world
> INFO: Elapsed time: 4.330s, Critical Path: 0.19s
> INFO: 2 processes: 2 darwin-sandbox.
> INFO: Build completed successfully, 3 total actions

# bazel-bin/main の中に build し終わったバイナリデータがある.
bazel-bin/main/hello-world
> Hello World.
> ABC
> 日本語でも大丈夫
```
