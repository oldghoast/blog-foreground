<template>
    <el-container>
        <el-header>
            <el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal" @select="handleSelect" style="padding-left: 10%;">
                <el-menu-item index="1" disabled>logo</el-menu-item>
                <el-menu-item index="2">首页</el-menu-item>
                <el-menu-item index="3">分类</el-menu-item>
                <el-menu-item index="4">关于</el-menu-item>
            </el-menu>
        </el-header>
        <el-main style="background-color: #F5F5F5;padding-left: 5%;padding-right: 5%;">
            <el-row :gutter="20">
                <el-col :span="5" :xs="0">
                    <el-row>
                        <el-col :span="24">
                            <div class="grid-content bg-purple">
                                <div class="card-content">
                                    <el-container>
                                        <el-header style="height: 100%;text-align: center;">
                                            <div>
                                                <el-avatar :size="128" src="http://cdn.oldghoast.top/head.jpg"></el-avatar>
                                            </div>
                                            <span style="font-weight: 400;font-size: 1.5rem !important;">
                                        oldghoast
                                    </span>
                                        </el-header>
                                        <el-main style="height: 100%;text-align: center;">
                                            <el-row class="heading">
                                                <el-col :span="8">
                                                    <div>
                                                        <el-container>
                                                            <el-header  style="height: 100%;">
                                                                文章
                                                            </el-header>
                                                            <el-main>
                                                                12
                                                            </el-main>
                                                        </el-container>
                                                    </div>
                                                </el-col>
                                                <el-col :span="8">
                                                    <div>
                                                        <el-container>
                                                            <el-header  style="height: 100%;">
                                                                文章
                                                            </el-header>
                                                            <el-main>
                                                                12
                                                            </el-main>
                                                        </el-container>
                                                    </div>
                                                </el-col>
                                                <el-col :span="8">
                                                    <div>
                                                        <el-container>
                                                            <el-header style="height: 100%;">
                                                                文章
                                                            </el-header>
                                                            <el-main>
                                                                12
                                                            </el-main>
                                                        </el-container>
                                                    </div>
                                                </el-col>
                                            </el-row>
                                            <el-row>
                                                <el-col :span="24">
                                                    <el-row>
                                                        <el-button size="mini" type="success" icon="el-icon-check" circle></el-button>
                                                        <el-button size="mini" type="info" icon="el-icon-message" circle></el-button>
                                                        <el-button size="mini" type="warning" icon="el-icon-star-off" circle></el-button>
                                                        <el-button size="mini" type="danger" icon="el-icon-delete" circle></el-button>
                                                    </el-row>
                                                </el-col>
                                            </el-row>
                                        </el-main>
                                    </el-container>
                                </div>
                            </div>
                        </el-col>
                        <el-col :span="24" style="margin-top: 1.5rem;">
                            <div class="grid-content bg-purple">
                                <div class="card-content">
                                    <el-container>
                                        <el-header style="height: 100%;padding:0 0">
                                            <i class="el-icon-collection-tag">
                                                分类
                                            </i>
                                        </el-header>
                                        <div style="margin: -20px 0;">
                                            <el-divider></el-divider>
                                        </div>
                                        <el-main style="height: 100%;padding:0 0;">
                                            <el-link>
                                                <i class="el-icon-view el-icon--right">
                                                    阴阳师 (12)
                                                </i>
                                            </el-link><br>
                                            <el-link>
                                                <i class="el-icon-view el-icon--right">
                                                    JAVA (12)
                                                </i>
                                            </el-link><br>
                                            <el-link>
                                                <i class="el-icon-view el-icon--right">
                                                    springboot (12)
                                                </i>
                                            </el-link><br>
                                            <el-link>
                                                <i class="el-icon-view el-icon--right">
                                                    数据库 (12)
                                                </i>
                                            </el-link><br>
                                        </el-main>
                                    </el-container>
                                </div>
                            </div>
                        </el-col>
                    </el-row>
                </el-col>
                <el-col :span="14" :xs="24">
                    <div class="grid-content bg-purple" style="background-color: #F5F5F5;">
                        <el-row class="el-row2">
                            <el-col :span="24">
                                <div class="bg-purple" style="height: 150px;">
                                    <el-container style="padding: 20px;">
                                        <el-aside style="width: 30%;height: 110px;">
                                            <el-image style="width: 100%; height: 100%;display: block" src="https://ok.166.net/reunionpub/ds/kol/20210205/212640-e0f2atr9cb.png?imageView&thumbnail=600x0&type=jpg"></el-image>
                                        </el-aside>
                                        <el-main style="padding: 0 0 0 15px">
                                            <el-row>
                                                <el-col :span="24" style="width: 100%;height: 22px;overflow: hidden;text-overflow: ellipsis;white-space:nowrap">
                                                    <span>
                                                        网易大神春节系列活动来袭，送上全网最神气过年指南！
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="width: 100%;height: 44px;overflow: hidden;text-overflow: ellipsis;display: -webkit-box;-webkit-line-clamp: 2;-webkit-box-orient: vertical;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        新春已至，许多小伙伴都做好了假期的快乐规划！虽然有不能出门旅游的遗憾，但新年的喜悦也似乎没有被冲淡！
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="height: 22px;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        <i class="el-icon-time"> 发表于：2020-01-01</i>
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="text-align: right;height: 22px;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        阅读全文
                                                        <i class="el-icon-d-arrow-right"></i>
                                                    </span>
                                                </el-col>
                                            </el-row>
                                        </el-main>
                                    </el-container>
                                </div>
                            </el-col>
                        </el-row>
                        <el-row class="el-row2">
                            <el-col :span="24">
                                <div class="bg-purple" style="height: 150px;">
                                    <el-container style="padding: 20px;">
                                        <el-aside style="width: 30%;height: 110px;">
                                            <el-image style="width: 100%; height: 100%;display: block" src="https://ok.166.net/reunionpub/ds/kol/20210205/212640-e0f2atr9cb.png?imageView&thumbnail=600x0&type=jpg"></el-image>
                                        </el-aside>
                                        <el-main style="padding: 0 0 0 15px">
                                            <el-row>
                                                <el-col :span="24" style="width: 100%;height: 22px;overflow: hidden;text-overflow: ellipsis;white-space:nowrap">
                                                    <span>
                                                        网易大神春节系列活动来袭，送上全网最神气过年指南！
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="width: 100%;height: 44px;overflow: hidden;text-overflow: ellipsis;display: -webkit-box;-webkit-line-clamp: 2;-webkit-box-orient: vertical;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        新春已至，许多小伙伴都做好了假期的快乐规划！虽然有不能出门旅游的遗憾，但新年的喜悦也似乎没有被冲淡！
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="height: 22px;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        <i class="el-icon-time"> 发表于：2020-01-01</i>
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="text-align: right;height: 22px;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        阅读全文
                                                        <i class="el-icon-d-arrow-right"></i>
                                                    </span>
                                                </el-col>
                                            </el-row>
                                        </el-main>
                                    </el-container>
                                </div>
                            </el-col>
                        </el-row>
                        <el-row class="el-row2">
                            <el-col :span="24">
                                <div class="bg-purple" style="height: 150px;">
                                    <el-container style="padding: 20px;">
                                        <el-aside style="width: 30%;height: 110px;">
                                            <el-image style="width: 100%; height: 100%;display: block" src="https://ok.166.net/reunionpub/ds/kol/20210205/212640-e0f2atr9cb.png?imageView&thumbnail=600x0&type=jpg"></el-image>
                                        </el-aside>
                                        <el-main style="padding: 0 0 0 15px">
                                            <el-row>
                                                <el-col :span="24" style="width: 100%;height: 22px;overflow: hidden;text-overflow: ellipsis;white-space:nowrap">
                                                    <span>
                                                        网易大神春节系列活动来袭，送上全网最神气过年指南！
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="width: 100%;height: 44px;overflow: hidden;text-overflow: ellipsis;display: -webkit-box;-webkit-line-clamp: 2;-webkit-box-orient: vertical;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        新春已至，许多小伙伴都做好了假期的快乐规划！虽然有不能出门旅游的遗憾，但新年的喜悦也似乎没有被冲淡！
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="height: 22px;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        <i class="el-icon-time"> 发表于：2020-01-01</i>
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="text-align: right;height: 22px;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        阅读全文
                                                        <i class="el-icon-d-arrow-right"></i>
                                                    </span>
                                                </el-col>
                                            </el-row>
                                        </el-main>
                                    </el-container>
                                </div>
                            </el-col>
                        </el-row>
                        <el-row class="el-row2">
                            <el-col :span="24">
                                <div class="bg-purple" style="height: 150px;">
                                    <el-container style="padding: 20px;">
                                        <el-aside style="width: 30%;height: 110px;">
                                            <el-image style="width: 100%; height: 100%;display: block" src="https://ok.166.net/reunionpub/ds/kol/20210205/212640-e0f2atr9cb.png?imageView&thumbnail=600x0&type=jpg"></el-image>
                                        </el-aside>
                                        <el-main style="padding: 0 0 0 15px">
                                            <el-row>
                                                <el-col :span="24" style="width: 100%;height: 22px;overflow: hidden;text-overflow: ellipsis;white-space:nowrap">
                                                    <span>
                                                        网易大神春节系列活动来袭，送上全网最神气过年指南！
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="width: 100%;height: 44px;overflow: hidden;text-overflow: ellipsis;display: -webkit-box;-webkit-line-clamp: 2;-webkit-box-orient: vertical;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        新春已至，许多小伙伴都做好了假期的快乐规划！虽然有不能出门旅游的遗憾，但新年的喜悦也似乎没有被冲淡！
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="height: 22px;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        <i class="el-icon-time"> 发表于：2020-01-01</i>
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="text-align: right;height: 22px;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        阅读全文
                                                        <i class="el-icon-d-arrow-right"></i>
                                                    </span>
                                                </el-col>
                                            </el-row>
                                        </el-main>
                                    </el-container>
                                </div>
                            </el-col>
                        </el-row>
                        <el-row class="el-row2">
                            <el-col :span="24">
                                <div class="bg-purple" style="height: 150px;">
                                    <el-container style="padding: 20px;">
                                        <el-aside style="width: 30%;height: 110px;">
                                            <el-image style="width: 100%; height: 100%;display: block" src="https://ok.166.net/reunionpub/ds/kol/20210205/212640-e0f2atr9cb.png?imageView&thumbnail=600x0&type=jpg"></el-image>
                                        </el-aside>
                                        <el-main style="padding: 0 0 0 15px">
                                            <el-row>
                                                <el-col :span="24" style="width: 100%;height: 22px;overflow: hidden;text-overflow: ellipsis;white-space:nowrap">
                                                    <span>
                                                        网易大神春节系列活动来袭，送上全网最神气过年指南！
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="width: 100%;height: 44px;overflow: hidden;text-overflow: ellipsis;display: -webkit-box;-webkit-line-clamp: 2;-webkit-box-orient: vertical;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        新春已至，许多小伙伴都做好了假期的快乐规划！虽然有不能出门旅游的遗憾，但新年的喜悦也似乎没有被冲淡！
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="height: 22px;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        <i class="el-icon-time"> 发表于：2020-01-01</i>
                                                    </span>
                                                </el-col>
                                                <el-col :span="24" style="text-align: right;height: 22px;">
                                                    <span style="font-size: 14px;color: #666;">
                                                        阅读全文
                                                        <i class="el-icon-d-arrow-right"></i>
                                                    </span>
                                                </el-col>
                                            </el-row>
                                        </el-main>
                                    </el-container>
                                </div>
                            </el-col>
                        </el-row>
                        <el-row>
                            <el-col :xs="24">
                                <el-pagination
                                        :small="paginationFlag"
                                        :pager-count="5"
                                        background
                                        layout="prev, pager, next"
                                        :total="1000" style="text-align: center;">
                                </el-pagination>
                            </el-col>
                        </el-row>
                    </div>
                </el-col>
                <el-col :span="5" :xs="0">
                    <el-row>
                        <el-col :span="24">
                            <div class="grid-content bg-purple">
                                <div class="card-content">
                                    <el-container>
                                        <el-header style="height: 100%;padding:0 0">
                                            <i class="el-icon-user">
                                                关注个人微信公众号
                                            </i>
                                        </el-header>
                                        <div style="margin: -20px 0;">
                                            <el-divider></el-divider>
                                        </div>
                                        <el-main style="height: 100%;padding:0 0;">
                                            <el-image style="width: 100%; height: 100%" :src="url">
                                            </el-image>
                                        </el-main>
                                    </el-container>
                                </div>
                            </div>
                        </el-col>
                        <el-col :span="24" style="margin-top: 1.5rem;">
                            <div class="grid-content bg-purple">
                                <div class="card-content">
                                    <el-container>
                                        <el-header style="height: 100%;padding:0 0">
                                            <i class="el-icon-date">
                                                归档
                                            </i>
                                        </el-header>
                                        <div style="margin: -20px 0;">
                                            <el-divider></el-divider>
                                        </div>
                                        <el-main style="height: 100%;padding:0 0;">
                                            <el-link>
                                                <i class="el-icon-view el-icon--right">
                                                    2021年1月11日 (12)
                                                </i>
                                            </el-link><br>
                                            <el-link>
                                                <i class="el-icon-view el-icon--right">
                                                    2021年1月11日 (12)
                                                </i>
                                            </el-link><br>
                                            <el-link>
                                                <i class="el-icon-view el-icon--right">
                                                    2021年1月11日 (12)
                                                </i>
                                            </el-link><br>
                                            <el-link>
                                                <i class="el-icon-view el-icon--right">
                                                    2021年1月11日 (12)
                                                </i>
                                            </el-link><br>
                                        </el-main>
                                    </el-container>
                                </div>
                            </div>
                        </el-col>
                    </el-row>
                </el-col>
            </el-row>
        </el-main>
        <el-footer style="height: 100%">
            <el-row>
                <el-col :span="24">
                    <div class="grid-content" style="text-align: left;margin-top: 30px;margin-left: 5%">
                        <div class="level-start">
                            <div>
                                <img src="https://blog.zhangruipeng.me/hexo-theme-icarus/img/logo.svg" alt="Icarus" height="28">
                            </div>
                            <span class="is-size-7">
                                <span>© 2021 PPOffice</span>
                                &nbsp;&nbsp;Powered by cxb
                            </span>
                        </div>
                    </div>
                </el-col>
            </el-row>
        </el-footer>
    </el-container>
</template>

<script>
    export default {
        name: "Main",
        data() {
            return {
                activeIndex: '2',
                paginationFlag: this.isMobile(),
                url: 'http://cdn.oldghoast.top/qrcode_for_gh_4244f4080339_258.jpg'
            };
        },
        methods: {
            handleSelect(key, keyPath) {
                console.log(key, keyPath);
            },
            isMobile() {
                return document.documentElement.clientWidth <= 640;
            }
        }
    }
</script>

<style scoped>
    .bg-purple {
        background: white;
    }
    .grid-content {
        border-radius: 4px;
        min-height: 36px;
    }
    .card-content {
        background-color: transparent;
        padding: 1.5rem;
    }
    .heading {
        display: block;
        font-size: 11px;
        letter-spacing: 1px;
        margin-bottom: 5px;
        text-transform: uppercase;
    }
    .el-row2 {
        margin-bottom: 20px;
    }
    .is-size-7 {
        font-size: 0.85rem !important;
        padding-bottom: 20px;
    }
</style>