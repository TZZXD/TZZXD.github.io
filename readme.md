## 本地预览指令

docker run -it --rm -p 4000:4000  -v $(pwd):/omd quay.io/omd/jekyll sh -c "bundle install; jekyll serve --host=0.0.0.0 --livereload"