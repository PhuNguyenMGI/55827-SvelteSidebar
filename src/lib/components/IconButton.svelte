<script>
import Happy from "$lib/images/happy-outline.svg";
import Sad from "$lib/images/sad-outline.svg";
import CodeSlash from "$lib/images/code-slash-outline.svg";
import Sync from "$lib/images/sync-outline.svg";
</script>

<div class="sidebar">
	<div class="item" data-tooltip="Item 1 🤔">
		<div class="circle">
            <img src={Happy} class="icon" alt="Happy face">
        </div>
	</div>
	<div class="item" data-tooltip="Item 2 🤔">
		<div class="circle">
            <img src={CodeSlash} class="icon" alt="Code slash">
        </div>
	</div>
	<div class="item" data-tooltip="Item 3 🤔">
		<div class="circle">
            <img src={Sad} class="icon" alt="Sad face">
        </div>
	</div>
	<div class="item" data-tooltip="Item 4 🤔">
		<div class="circle">
            <img src={Sync} class="icon" alt="Sync">
        </div>
	</div>
</div>
