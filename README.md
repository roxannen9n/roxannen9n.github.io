# Roxanne (Thao) Nguyen — personal website

## Chỉnh nội dung ngay trên GitHub

1. Mở `dist/index.html`, bấm biểu tượng bút chì **Edit this file**.
2. Tìm đoạn chữ muốn sửa (Ctrl+F), thay phần chữ giữa các thẻ HTML. Ví dụ `<p>Hello</p>` → `<p>Hi, I'm Roxanne.</p>`.
3. Bấm **Commit changes**, chọn commit vào `main`.
4. Chờ workflow trong tab **Actions** chạy xong rồi refresh website. Có thể cần vài phút.

Không cần cài phần mềm. Màu và font nằm trong `dist/style.css`. Muốn đổi CV, upload đè `dist/assets/Resume.pdf` cùng tên. Các nút GitHub của ba dự án nằm trong thuộc tính `href` của từng link trong `dist/index.html`.

Link sửa nhanh sau khi xuất bản: https://github.com/roxannen9n/roxannen9n.github.io/edit/main/dist/index.html

A small, static academic portfolio. All three selected projects link to their repositories on `github.com/roxannen9n`.

## Edit

- `dist/index.html`: biography, education, project descriptions, links.
- `dist/style.css`: colors, typography, responsive layout.
- `dist/assets/Resume.pdf`: CV copied from the public GitHub profile.
- `dist/assets/selected_trees.png`: result figure from the shading project.

No dependencies or build step. To preview: `python -m http.server 8080 --directory dist`.

## Publish on GitHub Pages

1. Create the repository `roxannen9n.github.io` for the address `https://roxannen9n.github.io/`.
2. Push this folder's `dist/`, `.github/`, `.gitignore`, and README to its `main` branch.
3. In repository Settings → Pages, select **GitHub Actions** as the source.
4. Run the “Deploy portfolio to GitHub Pages” workflow, or push a change to `main`.

The supplied workflow publishes `dist/` and updates the website after each push. Relative asset paths also work in a differently named project repository. `.openai/` is for the separate Sites service and is excluded from GitHub.

Content source: https://github.com/roxannen9n/roxannen9n . Layout inspired by the academic portfolio at https://tulliavu.github.io/vutrucquynh.github.io/ ; implemented independently. No publications, qualifications, or personal details have been added beyond the public profile.
