<style>
    /* Add alt attribute to img element */
    img[alt="Dashboard"] {
        alt: "Dashboard Widget";
    }
    /* Add alt attribute to img element */
    img[alt="GitHub WidgetBox"] {
        alt: "GitHub Skills Widget";
    }
    /* Add media queries for different screen sizes */
    @media only screen and (max-width: 768px) {
        img {
            width: 100%;
        }
    }
    @media only screen and (max-width: 576px) {
        /* Add styles for smaller screens, such as mobile devices */
    }
    @media only screen and (min-width: 769px) and (max-width: 992px) {
        /* Add styles for larger screens, such as tablets */
    }
    @media only screen and (min-width: 993px) {
        /* Add styles for even larger screens, such as laptops and desktops */
    }
</style>

<section>
    <div align="center">
        <img src="https://github-widgetbox.vercel.app/api/profile?username=damianodoug&data=followers,repositories,stars,commits&theme=aether" alt="Dashboard Widget">
    </div>
    <div>
        <img width="49%" src="https://github-widgetbox.vercel.app/api/skills?names=html,css,javascript,python,go,mysql,postgresql&includeNames=true&theme=aether" alt="GitHub Skills Widget" />
        <img width="49%" src="https://github-widgetbox.vercel.app/api/skills?tools=mongodb,docker,apache,nginx,nodejs,heroku,aws&includeNames=true&theme=aether" alt="GitHub Skills Widget" />
    </div>
    <hr>
    <!-- <div>
        <img src="https://github-readme-stats.vercel.app/api?username=damianodoug&show_icons=true&hide_border=true&bg_color=101820&icon_color=cf6bdd&text_color=bfbfbf&border_radius=10&include_all_commits=true&count_private=true&custom_title=Satus&title_color=cf6bdd&text_bold=false&layout=compact">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=damianodoug&layout=compact&hide_border=true&bg_color=101820&icon_color=cf6bdd&text_color=bfbfbf&border_radius=10&title_color=cf6bdd&text_bold=false"/>
    </div> -->
</section>