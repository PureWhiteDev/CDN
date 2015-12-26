这个仓库就当成公开网盘用了，可以用 git lfs 上传大文件

附：
1. git lfs 使用备忘
        
        # 首次需要设置
        git lfs install
        # 选择要用 Git LFS 管理的文件类型，比如 .mp4
        git lfs track "*.mp4"
        # 然后就像往常一样提交文件
        git add snow_white_with_the_red_hair_2_pv.mp4
        git commit -m "add snow white pv video"
        git push

2. 分享出去的文件 url 快速拼凑
        
        # https://github.com/PureWhiteDev/CDN/raw/master/path-to-file，接上例
        https://github.com/PureWhiteDev/CDN/raw/master/snow_white_with_the_red_hair_2_pv.mp4
