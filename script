function showCharacter(characterId) {
    // 隱藏所有頁面
    document.querySelectorAll('.page').forEach(page => {
        page.classList.remove('active');
    });
    
    // 顯示選中的角色頁面
    document.getElementById(characterId).classList.add('active');
    
    // 滾動到頁面頂部
    window.scrollTo(0, 0);
}

function showHome() {
    // 隱藏所有頁面
    document.querySelectorAll('.page').forEach(page => {
        page.classList.remove('active');
    });
    
    // 顯示主頁
    document.getElementById('home').classList.add('active');
    
    // 滾動到頁面頂部
    window.scrollTo(0, 0);
}

// 添加一些互動效果
document.addEventListener('DOMContentLoaded', function() {
    // 為卡片添加點擊動畫
    document.querySelectorAll('.character-card').forEach(card => {
        card.addEventListener('click', function() {
            this.style.transform = 'scale(0.95)';
            setTimeout(() => {
                this.style.transform = '';
            }, 150);
        });
    });
});