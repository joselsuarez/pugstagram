<script>
  export let nickname;
  export let name;  
</script>

<style>
    .Profile-content {
      display: flex;
      align-items: center;
    }
    .Profile-avatar img {
      width: 42px;
      height: 42px;
      border-radius: 50%;
    }
    .Profile-info {
      margin: 0 0 0 0.5em;
    }
    .Profile-info h2 {
      font-size: 14px;
      color: black;
      margin: 0;
      padding: 0;
    }
    .Profile-info span {
      font-size: 12px;
      font-weight: normal;
    }
</style>

<div class="Profile">
    <div class="Profile-content">
        <div class="Profile-avatar">
            <img src="https://titles.trackercdn.com/valorant-api/agents/7f94d92c-4234-0a36-9646-3a87eb8b5c89/displayicon.png" alt="" />
        </div>
        <div class="Profile-info">
            <h2>{nickname}</h2>
            <span>{name}</span>
        </div>
    </div>
</div>