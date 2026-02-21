 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
new file mode 100644
index 0000000000000000000000000000000000000000..bc0aafbb7859931bf195923c1b22c21a7da5c3fd
--- /dev/null
+++ b/README.md
@@ -0,0 +1,30 @@
+# Healthy Habits Lists
+
+A simple HTML/CSS project that demonstrates:
+
+- An **ordered list** for a morning routine
+- An **unordered list** for healthy foods
+
+## Files
+
+- `1.html` — page structure and list content
+- `1.css` — basic styling for the page, headings, and lists
+
+## Preview Locally
+
+Open `1.html` in any web browser.
+
+Examples:
+
+- Double-click `1.html`
+- Or run a local static server (optional), e.g.:
+
+```bash
+python3 -m http.server 8000
+```
+
+Then visit `http://localhost:8000/1.html`.
+
+## Notes
+
+This is a beginner-friendly exercise focused on basic HTML lists and CSS styling.
 
EOF
)
