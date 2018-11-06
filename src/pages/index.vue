<template>
    <div>
        <!-- nav -->
        <nav class="header-top" uk-navbar>
            <div class="uk-navbar-left">

                <a class="uk-navbar-item uk-logo" href="#">
                    <img data-src="../static/linkedin.png" width="40" uk-img>
                </a>
                <div class="uk-navbar-item relative" style="width:350px">
                    <form class="uk-search is-fullwidth uk-search-default" @click="detailSearch">
                        <span uk-search-icon></span>
                        <input class="uk-search-input back-white" type="search" placeholder="Search...">
                    </form>
                    <div :class="['search-detail', {none: searchDetail ? false : true}]">
                        <div>Search for</div>
                        <ul class="uk-list">
                            <li>
                                <span uk-icon="users" class="text-blue"></span>
                                <span class="ml0h"> People</span>
                            </li>
                            <li>
                                <span uk-icon="album" class="text-blue"></span>
                                <span class="ml0h">Jobs</span>
                            </li>
                            <li>
                                <span uk-icon="comments" class="text-blue"></span>
                                <span class="ml0h">Posts</span>
                            </li>
                        </ul>
                        <hr>
                        <div class="uk-clearfix">
                            <div class="uk-float-left">
                                <span class="uk-text-bold">Recent</span> 
                            </div>
                            <div class="uk-float-right">
                                <span>Clear</span>
                            </div>
                        </div>
                        <div class="uk-flex flex-center list-search mt1" >
                            <div class="account-search relative">
                                <img data-src="../static/profile.jpg" width="30" uk-img>
                            </div>
                            <div class="account-title uk-text-left ml0h">
                                <div class="uk-card-title mb0 name">Maria Vania</div>
                            </div>
                        </div>
                        <div class="uk-flex flex-center list-search">
                            <div class="account-search relative">
                                <img data-src="../static/profile.jpg" width="30" uk-img>
                            </div>
                            <div class="account-title uk-text-left ml0h">
                                <div class="uk-card-title mb0 name">Maria Vania</div>
                            </div>
                        </div>
                        <div class="uk-flex flex-center list-search">
                            <div class="account-search relative">
                                <img data-src="../static/profile.jpg" width="30" uk-img>
                            </div>
                            <div class="account-title uk-text-left ml0h">
                                <div class="uk-card-title mb0 name">Maria Vania</div>
                            </div>
                        </div>
                        <div class="uk-flex flex-center list-search">
                            <div class="account-search relative">
                                <img data-src="../static/profile.jpg" width="30" uk-img>
                            </div>
                            <div class="account-title uk-text-left ml0h">
                                <div class="uk-card-title mb0 name">Maria Vania</div>
                            </div>
                        </div>
                        <div class="uk-flex flex-center list-search">
                            <div class="account-search relative">
                                <img data-src="../static/profile.jpg" width="30" uk-img>
                            </div>
                            <div class="account-title uk-text-left ml0h">
                                <div class="uk-card-title mb0 name">Maria Vania</div>
                            </div>
                        </div>
                    </div>
                </div>
                
            </div>
            <div class="uk-navbar-right">
                
                <ul class="uk-navbar-nav">
                    <li class="is-active">
                        <a href="#">
                            <div class="uk-text-center">
                                <div class="uk-icon" uk-icon="icon: home"></div>
                                <div>Home</div>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="uk-text-center">
                                <div class="uk-icon relative" uk-icon="icon: users">
                                    <span class="uk-badge custom">1</span>
                                </div>
                                <div>My Network</div>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="uk-text-center">
                                <div class="uk-icon" uk-icon="icon: star"></div>
                                <div>Jobs</div>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="uk-text-center">
                                <div class="uk-icon" uk-icon="icon: comments"></div>
                                <div>Messaging</div>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="uk-text-center">
                                <div class="uk-icon relative" uk-icon="icon: bell">
                                    <span class="uk-badge custom">4</span>
                                </div>
                                <div>Notification</div>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="uk-text-center">
                                <div class="uk-icon" uk-icon="icon: star"></div>
                                <div>Me</div>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="uk-text-center">
                                <div class="uk-icon" uk-icon="icon: grid"></div>
                                <div>Work</div>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="uk-text-center">
                                <div class="text-gold">Free Upgrade <br> to Premium</div>
                            </div>
                        </a>
                    </li>
                </ul>

            </div>
        </nav>
        <!-- grid -->
        <div class="uk-container uk-margin-medium-top mb2">
            <div class="uk-text-center" uk-grid>
                <div class="uk-width-1-4">
                    <div class="uk-card uk-card-default uk-card-body no-padding">
                        <div class="account relative">
                            <div class="pic-account">
                                <img data-src="../static/profile.jpg" width="40" uk-img>
                            </div>
                        </div>
                        <div class="account-desc">
                            <h3 class="uk-card-title mb0">Maria Vania</h3>
                            <p class="mt0">Presenter</p>
                        </div>
                        <div class="account-info">
                            <h3 class="uk-card-title mb0 text-blue">80</h3>
                            <p class="mt0">Who's viewed your profile</p>
                        </div>
                        <div class="account-info">
                            <h3 class="uk-card-title mb0 text-blue">1,113</h3>
                            <p class="mt0 mb0">Connections</p>
                            <div class="uk-text-small uk-text-bold mt0 mb20">Manage your network</div>
                        </div>
                        <div class="account-add">
                            <p class="mt0 mb0">Access exclusive tools &amp; insights</p>
                            <div class="uk-text-small uk-text-bold mt0 mb20">
                                <span class="premium">Free Upgrade yo Premium</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="uk-width-1-2">
                    <div class="uk-card uk-card-default uk-card-body">
                        <div class="search">
                            <form class="uk-search is-fullwidth">
                                <input class="uk-search-input is-fullwidth" type="text" placeholder="Share an article, photo, video or idea">
                            </form>
                        </div>
                        <div class="search-label">
                            <div class="uk-clearfix">
                                <div class="uk-float-left">
                                    <span class="uk-label outline pointer">
                                        <span uk-icon="icon: file-edit"></span>
                                        <span class="ml0h"> Write an article</span>
                                    </span>
                                    <span class="uk-label outline pointer">
                                        <span uk-icon="icon: image"></span>
                                        <span class="ml0h">Images</span>
                                    </span>
                                    <span class="uk-label outline pointer">
                                        <span uk-icon="icon: video-camera"></span>
                                        <span class="ml0h">Video</span>
                                    </span>
                                </div>
                                <div class="uk-float-right">
                                    <button class="uk-button uk-button-primary uk-button-small mt10">Post</button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="divider uk-text-right mt10">
                        Sort by: <b class="pointer">Top</b> <span uk-icon="icon: triangle-down"></span>
                    </div>
                    <div class="uk-card uk-card-default uk-card-body mt10">
                        <div class="uk-clearfix">
                            <div class="uk-float-left uk-flex">
                                <div class="account-card relative">
                                    <img data-src="../static/profile.jpg" width="40" uk-img>
                                    <div class="online"></div>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <div class="uk-card-title mb0 name">Maria Vania</div>
                                    <p class="mt0 mb0 job">Presenter</p>
                                    <p class="mt0 job">1d</p>
                                </div>
                            </div>
                            <div class="uk-float-right">
                                <span uk-icon="more"></span>
                            </div>
                        </div>
                        <div class="card-article uk-text-left">
                            <div class="card-pic">
                                <img data-src="../static/ai.jpeg" uk-img>
                            </div>
                            <div class="account-title uk-text-left pad1">
                                <div class="uk-card-title uk-text-bold mb0 name">Artificial Intelligence ( AI ), Dari Teknologi Abstrak Hingga Jadi 'Otak' Bisnis</div>
                                <p class="mt0 mb0 job">daily.oktagon.co.id</p>
                            </div>
                        </div>
                        <p class="mt0 mb0 uk-text-left mt10 job">1 Like</p>
                        <hr>
                        <div class="uk-clearfix">
                            <div class="uk-float-left flex">
                                <span class="uk-label no-outline pointer flex-center pl0">
                                    <span uk-icon="icon: check"></span>
                                    <span class="ml0h">Like</span>
                                </span>
                                <span class="uk-label no-outline pointer flex-center">
                                    <span uk-icon="icon: comment"></span>
                                    <span class="ml0h">Comment</span>
                                </span>
                                <span class="uk-label no-outline pointer flex-center">
                                    <span uk-icon="icon: social"></span>
                                    <span class="ml0h">Share</span>
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="uk-width-expand">
                    <div class="uk-card uk-card-default uk-card-body">
                        <div class="uk-clearfix">
                            <div class="uk-float-left">
                                <div>Add to your feed</div>
                            </div>
                            <div class="uk-float-right">
                                <span uk-icon="info"></span>
                            </div>
                        </div>
                        <div class="uk-clearfix mt1">
                            <div class="uk-float-left uk-flex">
                                <div class="account-card relative">
                                    <img data-src="../static/profile.jpg" width="40" uk-img>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <div class="uk-card-title mb0 name">Maria Vania</div>
                                    <p class="mt0 mb0 job">Presenter</p>
                                </div>
                            </div>
                            <div class="uk-float-right">
                                <button class="uk-button uk-button-default btn-follow">+ Follow</button>
                            </div>
                        </div>
                        <div class="uk-clearfix mt1">
                            <div class="uk-float-left uk-flex">
                                <div class="account-card relative">
                                    <img data-src="../static/profile.jpg" width="40" uk-img>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <div class="uk-card-title mb0 name">Maria Vania</div>
                                    <p class="mt0 mb0 job">Presenter</p>
                                </div>
                            </div>
                            <div class="uk-float-right">
                                <button class="uk-button uk-button-default btn-follow">+ Follow</button>
                            </div>
                        </div>
                        <div class="uk-clearfix mt1">
                            <div class="uk-float-left uk-flex">
                                <div class="account-card relative">
                                    <img data-src="../static/profile.jpg" width="40" uk-img>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <div class="uk-card-title mb0 name">Maria Vania</div>
                                    <p class="mt0 mb0 job">Presenter</p>
                                </div>
                            </div>
                            <div class="uk-float-right">
                                <button class="uk-button uk-button-default btn-follow">+ Follow</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import UIkit from 'uikit';
import Icons from 'uikit/dist/js/uikit-icons';
UIkit.use(Icons);

export default {
    data() {
        return {
            searchDetail: false
        }
    },
    methods: {
        detailSearch() {
            this.searchDetail = !this.searchDetail
        }
    }
}
</script>

<style>

</style>

