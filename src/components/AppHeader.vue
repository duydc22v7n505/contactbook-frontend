<template>
    <nav class="navbar navbar-expand navbar-dark bg-dark">
        <a href="/" class="navbar-brand">Ứng dụng Quản lý danh bạ</a>

        <div class="mr-auto navbar-nav">
            <li class="nav-item">
                <router-link :to="{ name: 'contactbook' }" class="nav-link">
                    Danh bạ
                    <i class="fas fa-address-book"></i>
                </router-link>
            </li>
        </div>
    </nav>
</template>

<script>
export default {
    // Component này hiện tại chỉ hiển thị giao diện tĩnh, chưa cần logic xử lý
};
</script>

<style scoped>
/* Bạn có thể thêm CSS tùy chỉnh cho thanh điều hướng tại đây nếu cần */
.navbar-brand {
    font-weight: bold;
}
</style>