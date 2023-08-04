# Cargo

- 创建 cargo 项目

  ```
    cargo new [project_name]
  ```

- 编译 cargo 项目并运行

  ```
    # 测试环境
    cargo build
    ./target/debug/[project_name]
    # 生产环境
    cargo build --release
    ./target/debug/[project_name]
  ```

- 开发环境运行 cargo 项目

  ```
    cargo run

  ```

- 快速检查代码是否有书写错误

  ```
    cargo check
  ```
