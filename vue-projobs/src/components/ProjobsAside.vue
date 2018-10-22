<template>
    <aside>
        <ul>
            <li>
                <div class="company_name">
                    <label for="company_name">회사명</label>
                    <input type="text" id="company_name">
                </div>
            </li>
            <li>
                <div class="tech_stack">
                    <label for="tech_stack">기술스택</label>
                    <input type="text" id="tech_stack">
                </div>
            </li>
            <li>
                <div class="assigned_task">
                    <label for="assigned_task">담당업무</label>
                    <input type="text" id="assigned_task">
                </div>
            </li>
            <li>
                <div class="job_link">
                    <a href="" class="link_job">링크</a>
                </div>
            </li>
            <li>
                <div class="type_period">
                    <button type="button">모집중</button>
                    <button type="button">지난공고</button>
                </div>
            </li>
        </ul>
    </aside>
</template>

<style scoped>
 aside {
     position:fixed;
     height: 100vh;
 }

 aside ul{
     display:flex;
     flex-direction: column;
     align-content: space-around
 }
 aside label,aside input{
     display:block;
 }
</style>

