<template>
  <div>
    <menu>
        <img src="@/assets/logo.png" width="90%" />
        <ul>
            <li class="selected">
                <a href="javascript:void(0);" @click="showIframe('workbeanch.html', $event)">
                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                        aria-hidden="true" role="img" class="icon iconify iconify--gitee" width="1em" height="1em"
                        preserveAspectRatio="xMidYMid meet" viewBox="0 0 16 16">
                        <g fill="none" fill-rule="evenodd">
                            <path d="M0 0h16v16H0z"></path>
                            <path fill="currentColor"
                                d="M15.416 7.386a2 2 0 010 2.828l-3.364 3.364-3.094.898a.5.5 0 01-.632-.632l.898-3.094 3.364-3.364a2 2 0 012.828 0zM6.5 8.5a1 1 0 01.993.883L7.5 9.5v4a1 1 0 01-.883.993L6.5 14.5h-4a1 1 0 01-.993-.883L1.5 13.5v-4a1 1 0 01.883-.993L2.5 8.5zm-.25 1h-3.5a.25.25 0 00-.25.25v3.5c0 .138.112.25.25.25h3.5a.25.25 0 00.25-.25v-3.5a.25.25 0 00-.25-.25zm6.12-.624-2.348 2.348-.636 2.19 2.192-.636 2.347-2.347zm.95-.94-.096.086-.247.247 1.555 1.555.248-.246a1.1 1.1 0 00.085-1.46l-.085-.096a1.1 1.1 0 00-1.46-.085zM6.5 1.5a1 1 0 01.993.883L7.5 2.5v4a1 1 0 01-.883.993L6.5 7.5h-4a1 1 0 01-.993-.883L1.5 6.5v-4a1 1 0 01.883-.993L2.5 1.5zm7 0a1 1 0 01.993.883l.007.117v2.835a3.52 3.52 0 00-1 0V2.75a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25v3.5c0 .138.112.25.25.25h1.601l-1 1H9.5a1 1 0 01-.993-.883L8.5 6.5v-4a1 1 0 01.883-.993L9.5 1.5zm-7.25 1h-3.5a.25.25 0 00-.25.25v3.5c0 .138.112.25.25.25h3.5a.25.25 0 00.25-.25v-3.5a.25.25 0 00-.25-.25z">
                            </path>
                        </g>
                    </svg>
                    <div>工作台</div>
                </a>
            </li>

            <li>
                <a class="portal-link" href="javascript:void(0);" @click="showMenuArea('base', $event)">
                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                        aria-hidden="true" role="img" class="icon iconify iconify--gitee" width="1em" height="1em"
                        preserveAspectRatio="xMidYMid meet" viewBox="0 0 16 16">
                        <g fill="none" fill-rule="evenodd">
                            <path d="M0 0h16v16H0z"></path>
                            <path fill="currentColor"
                                d="M14 4a.5.5 0 01.492.41l.008.09V14a1 1 0 01-1 1H5l-.09-.008a.5.5 0 010-.984L5 14h8.25a.25.25 0 00.243-.193l.007-.057V4.5l.008-.09A.5.5 0 0114 4zm-2.5-3a1 1 0 011 1v10a1 1 0 01-1 1h-9a1 1 0 01-1-1V2a1 1 0 011-1zm-.25 1h-8.5a.25.25 0 00-.243.193L2.5 2.25v9.5a.25.25 0 00.193.243L2.75 12h8.5a.25.25 0 00.243-.193l.007-.057v-9.5a.25.25 0 00-.25-.25zM7.333 8a.5.5 0 110 1H5a.5.5 0 010-1zM9 6a.5.5 0 010 1H5a.5.5 0 010-1zm0-2a.5.5 0 010 1H5a.5.5 0 010-1z">
                            </path>
                        </g>
                    </svg>
                    <div>门户管理</div>
                </a>
            </li>

<!--             <li>
                <a target="topFrame" href="../workflow">
                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                        aria-hidden="true" role="img" class="icon iconify iconify--gitee" width="1em" height="1em"
                        preserveAspectRatio="xMidYMid meet" viewBox="0 0 20 20">
                        <g fill="none" fill-rule="evenodd">

                            <path stroke="#5f6d84" stroke-linecap="round" stroke-linejoin="round" stroke-width="1"
                                d="M3 1h12M3 1v16M3 1H2m13 0v16m0-16h1m-1 16H3m12 0h2M3 17H1M6 4h1v1H6V4Zm5 0h1v1h-1V4ZM6 8h1v1H6V8Zm5 0h1v1h-1V8Zm-3 4h2a1 1 0 0 1 1 1v4H7v-4a1 1 0 0 1 1-1Z" />
                        </g>
                    </svg>
                    <div>Base管理</div>
                </a>
            </li> -->

            <li>
                <a class="model-link" href="javascript:void(0);" @click="showMenuArea('model', $event)">
                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                        aria-hidden="true" role="img" class="icon iconify iconify--gitee" width="1em" height="1em"
                        preserveAspectRatio="xMidYMid meet" viewBox="0 0 16 16">
                        <g fill="none" fill-rule="evenodd">
                            <path d="M0 0h16v16H0z"></path>
                            <path fill="currentColor"
                                d="M13 1a1 1 0 011 1v12a1 1 0 01-1 1H3a1 1 0 01-1-1V2a1 1 0 011-1zm0 12H3v.75a.25.25 0 00.193.243L3.25 14h9.5a.25.25 0 00.243-.193L13 13.75zM5 2H3.25a.25.25 0 00-.243.193L3 2.25V12h10V2.25a.25.25 0 00-.25-.25H10.5v5.621a.25.25 0 01-.348.23l-2.304-.985a.25.25 0 00-.196 0l-2.304.985A.25.25 0 015 7.621zm4.5 0H6v4.279a.15.15 0 00.162.15l.047-.012 1.482-.634a.15.15 0 01.079-.01l.039.01 1.482.634a.15.15 0 00.201-.09l.008-.048z">
                            </path>
                        </g>
                    </svg>
                    <div>业务建模</div>
                </a>
            </li>
  
            <li>
                <a target="topFrame" class="iam-link"  href="http://localhost:8081/?m=user">
                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                        aria-hidden="true" role="img" class="icon iconify iconify--gitee" width="24px" height="24px"
                        preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24">
                        <g fill="none" fill-rule="evenodd">
                            <path d="M16 7C16 9.20914 14.2091 11 12 11C9.79086 11 8 9.20914 8 7C8 4.79086 9.79086 3 12 3C14.2091 3 16 4.79086 16 7Z"
                            fill="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round"></path>
                            <path d="M12 14C8.13401 14 5 17.134 5 21H19C19 17.134 15.866 14 12 14Z"  fill="currentColor"
                                stroke-width="1" stroke-linecap="round" stroke-linejoin="round"></path>
                        </g>
                    </svg>
                    <div>用户管理</div>
                </a>
            </li>
            <li>
                <a href="javascript:void(0);" @click="showIframe('https://dev.ajaxjs.com/demo/ui-designer/', $event)">
                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                        aria-hidden="true" role="img" class="icon iconify iconify--gitee" width="1em" height="1em"
                        preserveAspectRatio="xMidYMid meet" viewBox="0 0 16 16">
                        <g fill="none" fill-rule="evenodd">
                            <path d="M0 0h16v16H0z"></path>
                            <path fill="currentColor"
                                d="M9.549 2.2a.5.5 0 01.353.612L7.055 13.437a.5.5 0 11-.966-.259L8.936 2.553a.5.5 0 01.613-.354zM5.24 3.745a.5.5 0 010 .708l-3.542 3.54 3.542 3.542a.5.5 0 01-.707.707l-3.89-3.89a.498.498 0 01-.144-.31v-.097a.498.498 0 01.145-.31l3.889-3.89a.5.5 0 01.707 0zm5.505 0a.5.5 0 01.708 0l3.889 3.89a.498.498 0 01.144.31v.097a.498.498 0 01-.144.31l-3.89 3.89a.5.5 0 01-.707-.707l3.542-3.542-3.542-3.54a.5.5 0 010-.708z">
                            </path>
                        </g>
                    </svg>
                    <div>UI设计器</div>
                </a>
            </li>

            <li>
                <a href="javascript:void(0);" @click="showIframe('https://dev.ajaxjs.com/demo/workflow/', $event)">
                    <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" class="icon iconify iconify--gitee" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                        viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" width="1.5em" height="1.5em">
                        <g>
                            <path fill="currentColor" d="M445.66,49.341H340.206L294.008,3.143c-4.192-4.191-10.99-4.191-15.183,0l-49.341,49.342
                           c-4.192,4.192-4.192,10.99,0,15.183l46.198,46.198v38.494h-80.516c-5.929,0-10.736,4.806-10.736,10.735v21.471h-42.942v-21.471
                           c0-5.929-4.806-10.735-10.736-10.735H66.34c-5.929,0-10.735,4.806-10.735,10.735v64.413c0,5.929,4.806,10.735,10.735,10.735
                           h20.755v93.798c0,5.929,4.806,10.736,10.735,10.736h95.437l-10.346,10.346c-4.192,4.192-4.193,10.99,0,15.182
                           c2.097,2.097,4.844,3.144,7.591,3.144c2.747,0,5.495-1.049,7.591-3.144l15.061-15.061c3.994,8.83,10.521,16.859,19.311,23.54
                           c11.932,9.068,26.987,14.783,43.205,16.539v32.792h-42.942c-5.929,0-10.735,4.806-10.735,10.736v64.413
                           c0,5.929,4.806,10.735,10.735,10.735h107.355c5.929,0,10.735-4.806,10.735-10.735v-64.413c0-5.929-4.806-10.736-10.735-10.736
                           h-42.942v-32.792c16.218-1.756,31.272-7.471,43.205-16.539c8.801-6.689,15.332-14.73,19.325-23.572l15.092,15.092
                           c2.097,2.097,4.844,3.144,7.591,3.144s5.495-1.049,7.591-3.144c4.192-4.192,4.192-10.99,0-15.182l-10.346-10.346h66.05
                           c5.929,0,10.736-4.806,10.736-10.736V60.077C456.396,54.148,451.589,49.341,445.66,49.341z M252.257,60.078l34.16-34.16
                           l34.16,34.16l-34.16,34.16L252.257,60.078z M205.901,173.832h161.032v42.942H205.901V173.832z M77.075,216.774v-42.942h42.942
                           v42.942H77.075z M213.249,310.922l-15.143-15.143c-4.192-4.192-10.99-4.192-15.183,0c-4.192,4.192-4.192,10.99,0,15.183
                           l10.346,10.346h-84.702v-83.063h22.187c5.929,0,10.735-4.806,10.735-10.735v-21.471h42.942v21.471
                           c0,5.929,4.806,10.735,10.735,10.735h80.516v32.792c-16.218,1.756-31.272,7.471-43.205,16.539
                           C223.75,294.208,217.25,302.168,213.249,310.922z M329.359,447.587v42.942h-85.884v-42.942H329.359z M286.417,372.439
                           c-31.078,0-56.361-18.059-56.361-40.258s25.283-40.258,56.361-40.258c31.078,0,56.361,18.059,56.361,40.258
                           S317.496,372.439,286.417,372.439z M379.61,321.308l10.347-10.346c4.192-4.192,4.192-10.99,0-15.183
                           c-4.192-4.191-10.99-4.191-15.183,0l-15.175,15.175c-4-8.766-10.505-16.738-19.242-23.378
                           c-11.932-9.068-26.987-14.783-43.205-16.539v-32.792h80.516c5.929,0,10.735-4.806,10.735-10.735v-64.413
                           c0-5.929-4.806-10.735-10.735-10.735h-80.516v-38.494l43.054-43.054h94.718v250.494H379.61z" />
                        </g>
                    </svg>
                    <div>流程管理</div>
                </a>
            </li>

            <li>
                <a target="topFrame" href="../database-doc/index.htm">
                    <svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg"
                        xmlns:xlink="http://www.w3.org/1999/xlink" class="icon iconify iconify--gitee" width="1em"
                        height="1em" x="0px" y="0px" viewBox="0 0 489.5 489.5"
                        style="enable-background:new 0 0 489.5 489.5;" xml:space="preserve">

                        <g fill="currentColor">
                            <rect y="1.35" width="97.5" height="97.5" />
                            <rect x="138.3" y="27.45" width="351.2" height="43.1" />
                            <rect y="195.95" width="97.5" height="97.5" />
                            <rect x="138.3" y="222.05" width="351.2" height="43.1" />
                            <rect y="390.65" width="97.5" height="97.5" />
                            <rect x="138.3" y="416.65" width="351.2" height="43.1" />
                        </g>

                    </svg>
                    <div>运维监控</div>
                </a>
            </li>

            <li class="bottom">
                <a target="topFrame" href="../database-doc/index.htm">
                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                        aria-hidden="true" role="img" class="icon iconify iconify--gitee" width="20" height="20"
                        preserveAspectRatio="xMidYMid meet" viewBox="0 0 16 16">
                        <g fill="none" fill-rule="evenodd">
                            <path d="M0 0h16v16H0z"></path>
                            <path fill="currentColor" fill-rule="nonzero"
                                d="M8 .5c.316 0 .656.026 1.023.074.474.072.863.398.967.824.207.604.513 1.012.916 1.248.442.259.858.383 1.251.383.151 0 .316-.019.5-.053a1.137 1.137 0 011.221.424c.36.463.659.948.887 1.442l.177.413c.04.118.058.242.058.366 0 .266-.083.54-.323.818-.788.851-.78 2.266.013 3.136.227.265.31.538.31.804 0 .166-.031.33-.092.451-.262.63-.61 1.23-1.022 1.761-.24.324-.585.475-.93.475-.098 0-.194-.016-.275-.037a2.578 2.578 0 00-.51-.058c-.406 0-.719.066-1.137.319-.488.273-.86.74-1.032 1.27-.116.468-.505.794-.989.867-.357.047-.697.073-1.013.073s-.656-.026-1.023-.074c-.474-.072-.863-.398-.967-.824-.207-.604-.513-1.012-.916-1.248-.442-.259-.858-.383-1.251-.383a2.78 2.78 0 00-.5.053 1.137 1.137 0 01-1.221-.424 7.602 7.602 0 01-1.016-1.74A1.08 1.08 0 011 10.38c0-.266.083-.54.325-.82.385-.412.596-.96.596-1.559 0-.6-.21-1.144-.62-1.573A1.25 1.25 0 011 5.62c0-.166.031-.33.09-.447a7.403 7.403 0 011.024-1.765c.24-.324.585-.475.93-.475.098 0 .194.016.269.036.214.04.379.06.53.06.393 0 .809-.125 1.25-.384.404-.236.71-.644.905-1.206.116-.468.505-.794.989-.867A7.821 7.821 0 018 .5zm0 1c-.268 0-.566.022-.873.063a.18.18 0 00-.151.106l-.109.293c-.283.697-.706 1.219-1.269 1.548-.587.343-1.174.52-1.755.52-.178 0-.356-.017-.574-.053l-.172-.031-.053-.012c-.046 0-.088.018-.133.08A6.555 6.555 0 002.125 5.3l-.123.283L2 5.621c0 .048.015.1.05.145.564.586.87 1.38.87 2.234 0 .85-.304 1.643-.851 2.226-.056.065-.069.108-.069.153 0 .023.003.04.016.068.227.549.53 1.07.901 1.548a.17.17 0 00.082.065l.045.006.083-.018c.27-.051.493-.077.716-.077.581 0 1.168.176 1.755.52.625.365 1.078.968 1.37 1.828.015.06.07.105.15.117.316.042.614.064.882.064s.566-.022.873-.063c.072-.01.12-.042.15-.101l.088-.247a3.255 3.255 0 011.42-1.663 2.92 2.92 0 011.64-.455c.169 0 .34.015.532.046l.2.037.053.012c.046 0 .088-.018.133-.08.292-.375.544-.784.757-1.229l.152-.34.002-.038a.206.206 0 00-.059-.142c-1.131-1.24-1.141-3.242-.01-4.463a.256.256 0 00.066-.12L14 5.622l-.007-.044-.152-.35a6.593 6.593 0 00-.758-1.222.17.17 0 00-.082-.065l-.045-.006-.083.018c-.27.051-.493.077-.716.077-.581 0-1.168-.176-1.755-.52-.625-.365-1.078-.968-1.37-1.828-.015-.06-.07-.105-.15-.117A6.843 6.843 0 008 1.5zM8 5a3 3 0 110 6 3 3 0 010-6zm0 1a2 2 0 100 4 2 2 0 000-4z">
                            </path>
                        </g>
                    </svg>
                    <div>系统管理</div>
                </a>
            </li>
        </ul>
    </menu>

    <!-- 登录控制 -->
    <div id="user-bar">
        <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img"
            class="icon iconify iconify--gitee" width="18px" height="18px" preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24">
            <g fill="none" fill-rule="evenodd">
                <path
                    d="M16 7C16 9.20914 14.2091 11 12 11C9.79086 11 8 9.20914 8 7C8 4.79086 9.79086 3 12 3C14.2091 3 16 4.79086 16 7Z"
                    stroke="#5f6d84" stroke-width="1" stroke-linecap="round" stroke-linejoin="round"></path>
                <path d="M12 14C8.13401 14 5 17.134 5 21H19C19 17.134 15.866 14 12 14Z" stroke="#5f6d84"
                    stroke-width="1" stroke-linecap="round" stroke-linejoin="round"></path>
            </g>
        </svg>

        <span v-if="jwtToken != null">
            <a href="user-info.html" target="topFrame">{{jwtToken.name}}</a>
            <div>已登录</div>
            <a href="#" @click="logout">登出</a>
            <a href="#">数据源</a>
            <select style="vertical-align: top;margin-top: 4px;">
                <option>不分租户</option>
                <option>IBM</option>
                <option>京东</option>
            </select>
        </span>

        <span v-if="jwtToken == null">
            <div>未登录</div>
            <a :href="loginUrl">用户登录</a>
        </span>
    </div>
    <iframe :src="iframeSrc" name="topFrame" frameborder="no" height="100%" v-if="isShowIframe"></iframe>
    <div class="menu-area" v-if="!isShowIframe">
        <Base v-if="load == 'base'" />
        <Model v-if="load == 'model'" />
    </div>
  </div>
</template>

<script>
import Base from "./menu/base.vue";
import Model from "./menu/model.vue";

export default {
    components:{
        Base, Model
    },
  data() {
    return {
        isShowIframe: true,
        iframeSrc: 'workbeanch.html',
        loginUrl: '',
        load:null,
        jwtToken: null
    };
  },

  methods: {
    showMenuArea(type, e) {
        this.isShowIframe = false;
        this.load = type;
        this._onSelect(e);
    },
    showIframe(url, e) {
        this.isShowIframe = true;
        this.iframeSrc = url;
        this._onSelect(e);
    },
    _onSelect(e) {
        let old = document.querySelector('li.selected');
        old.classList.remove('selected');
        e.currentTarget.parentNode.classList.add('selected');
    },
    routeTo(route) {
      location.hash = "#/" + route;
    },
    open(route) {
      window.open("#/" + route);
    },
  },
};
</script>

<style lang="less" src="./index.less" scoped></style>
<style lang="less">
.home h2,
.home p {
  max-width: 800px;
  margin: 10px auto;
}

html,
body,
.main > .ivu-menu {
    overflow: hidden;
    height: 100%;
}

.ivu-menu-submenu-title {
    border-top: 1px solid #eee;
}
</style>