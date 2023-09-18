<script lang="ts">
  let inputValue = "";
</script>

<input bind:value={inputValue} placeholder="8文字まで入力可" maxlength="8" class="outline rounded outline-1 outline-violet-400 p-1" />
<p>入力された文字列: {inputValue || ""}</p>
