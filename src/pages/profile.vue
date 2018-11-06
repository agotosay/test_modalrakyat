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
                        <input class="uk-search-input" type="search" placeholder="Search...">
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
        <div class="uk-container uk-margin-medium-top pb2">
            <div class="uk-text-center" uk-grid>
                <div class="uk-width-expand">
                    <div class="uk-card uk-card-default uk-card-body no-padding">
                        <div class="back-profile">
                            <div class="pic-profile">
                                <img data-src="../static/profile.jpg" uk-img>
                            </div>
                        </div>
                        <div class="content-profile mt60">
                            <div class="uk-clearfix">
                                <div class="uk-float-left">
                                    <div class="uk-text-left">
                                        <h3 class="uk-card-title mb0">Maria Vania<span class="position-title">2nd</span></h3>
                                        <h4 class="mb0 mt0">Presenter</h4>
                                        <p class="mt0">Indonesia</p>
                                    </div>
                                    <div uk-margin>
                                        <button class="uk-button uk-button-primary">Connect</button>
                                        <button class="uk-button uk-button-default text-blue">InMail</button>
                                        <button class="uk-button uk-button-default">More...</button>
                                    </div>

                                </div>
                                <div class="uk-float-right uk-text-left">
                                    <div>
                                        <span uk-icon="heart"></span>
                                        <span class="uk-text-small uk-text-bold">Binus University</span>
                                    </div>
                                    <div>
                                        <span uk-icon="thumbnails"></span>
                                        <span class="uk-text-small uk-text-bold">Binus</span>
                                    </div>
                                    <div>
                                        <span uk-icon="tablet"></span>
                                        <span class="uk-text-small uk-text-bold">See contact info</span>
                                    </div>
                                    <div>
                                        <span uk-icon="users"></span>
                                        <span class="uk-text-small uk-text-bold">500+ connections</span>
                                    </div>
                                </div>
                            </div>
                            <hr>
                            <p class="mt0 uk-text-left">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
                        </div>
                        <hr>
                        <a href="" class="mb20 block"><span>Show More</span><span uk-icon="icon:  chevron-down"></span></a>
                    </div>
                    <div class="uk-card uk-card-default uk-card-body no-padding mt1">
                        <div class="content-profile">
                            <h4 class="mb0 mt0 uk-text-left">Highlights</h4>
                            <div class="uk-column-1-2 mt1">
                                <div>
                                    <div class="uk-flex">
                                        <div class="account-card relative" style="width:80px">
                                            <img data-src="../static/profile.jpg" width="81" uk-img>
                                        </div>
                                        <div class="account-title uk-text-left ml0h">
                                            <div class="uk-card-title mb0 name uk-text-bold">85 mutual connections</div>
                                            <p class="mt0 mb0 job">You and Hantze both know Wenas Agussetiawan, Achmad Zaky, and 83 others</p>
                                        </div>
                                    </div>
                                </div>
                                <div>
                                    <div class="uk-flex">
                                        <div class="account-card relative" style="width:80px">
                                            <img data-src="../static/profile.jpg" width="81" uk-img>
                                        </div>
                                        <div class="account-title uk-text-left ml0h">
                                            <div class="uk-card-title mb0 name uk-text-bold">Reach out to Hanze for ...</div>
                                            <p class="mt0 mb0 job">Joining not profit</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            
                        </div>
                        <hr>
                        <a href="" class="mb20 block"><span>Show More</span><span uk-icon="icon:  chevron-down"></span></a>
                    </div>
                    <div class="uk-card uk-card-default uk-card-body no-padding mt1">
                        <div class="content-profile">
                            <div class="uk-clearfix mt1">
                                <div class="uk-float-left">
                                    <h4 class="mb0 mt0 uk-text-left">Hantze's Activity</h4>
                                    <p class="mt0 uk-text-left">1,151 Followers</p>
                                </div>
                                <div class="uk-float-right">
                                    <button class="uk-button uk-button-default btn-follow">+ Follow</button>
                                </div>
                            </div>
                            <div class="uk-flex">
                                <div class="account-card relative" style="width:180px">
                                    <img data-src="../static/profile.jpg" width="81" uk-img>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <p class="mt0 mb0">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
                                </div>
                            </div>
                            <a href="" class="mb20 block uk-text-left mt1 uk-text-bold"><span>See All Activity</span></a>
                        </div>
                    </div>
                    <div class="uk-card uk-card-default uk-card-body no-padding mt1">
                        <div class="content-profile">
                            <h4 class="mb0 mt0 uk-text-left">Experiences</h4>
                            <div class="uk-flex mt1">
                                <div class="account-card relative">
                                    <img data-src="../static/profile.jpg" width="81" uk-img>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <div class="uk-card-title mb0 name uk-text-bold">Presenter</div>
                                    <h5 class="mb0 mt0">Football Sport</h5>
                                    <p class="mt0 mb0 job">You and Hantze both know Wenas Agussetiawan, Achmad Zaky, and 83 others</p>

                                    <p class="mt0 mb0 mt1">Responsibility</p>
                                    <ul class="uk-list uk-list-bullet">
                                        <li>List item 1</li>
                                        <li>List item 2</li>
                                        <li>List item 3</li>
                                    </ul>
                                </div>
                            </div>
                            <a href="" class="mb20 block uk-text-left mt1 uk-text-bold"><span>Show More</span><span uk-icon="icon:  chevron-down"></span></a>
                        </div>
                        <hr>
                    </div>
                </div>
                <div class="uk-width-1-3">
                    <div class="uk-card uk-card-body no-padding">
                        <div class="content-profile">
                            <h4 class="mb0 mt0 uk-text-left">People Also Viewed</h4>
                            <div class="flex-center mt1">
                                <div class="account-card relative">
                                    <img data-src="../static/profile.jpg" width="40" uk-img>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <div class="uk-card-title mb0 name">Maria Vania</div>
                                    <p class="mt0 mb0 job">Presenter</p>
                                </div>
                            </div>
                            <div class="flex-center mt1">
                                <div class="account-card relative">
                                    <img data-src="../static/profile.jpg" width="40" uk-img>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <div class="uk-card-title mb0 name">Maria Vania <span class="position-title">2nd</span></div>
                                    <p class="mt0 mb0 job">Presenter</p>
                                </div>
                            </div>
                            <div class="flex-center mt1">
                                <div class="account-card relative">
                                    <img data-src="../static/profile.jpg" width="40" uk-img>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <div class="uk-card-title mb0 name">Maria Vania <span class="position-title">2nd</span></div>
                                    <p class="mt0 mb0 job">Presenter</p>
                                </div>
                            </div>
                            <div class="flex-center mt1">
                                <div class="account-card relative">
                                    <img data-src="../static/profile.jpg" width="40" uk-img>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <div class="uk-card-title mb0 name">Maria Vania <span class="position-title">2nd</span></div>
                                    <p class="mt0 mb0 job">Presenter</p>
                                </div>
                            </div>
                            <div class="flex-center mt1">
                                <div class="account-card relative">
                                    <img data-src="../static/profile.jpg" width="40" uk-img>
                                </div>
                                <div class="account-title uk-text-left ml0h">
                                    <div class="uk-card-title mb0 name">Maria Vania <span class="position-title">2nd</span></div>
                                    <p class="mt0 mb0 job">Presenter</p>
                                </div>
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

