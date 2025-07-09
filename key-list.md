# Key-List

## Table

<img width="1751" alt="cap 2025-07-09 09 46 30" src="https://github.com/user-attachments/assets/454346e1-36e9-4558-9231-63417ddfc59b" />

<!---
<style>
	table {
		border-collapse: collapse;
		font-family: sans-serif;
		font-size: 16px; /* 글자 크기 조정 */
		text-align: center;
		margin: 20px auto; /* 테이블 중앙 정렬 및 상하 여백 */
	}
	td {
		border: 1px solid #ccc;
		padding: 5px;
		min-width: 25px; /* 셀 최소 너비 */
		height: 30px; /* 셀 높이 */
		vertical-align: top; /* 내용 상단 정렬 */
	}
	td:empty {
		border-color: transparent; /* 빈 셀의 테두리 숨김 */
	}
	b {
		font-weight: bold;
	}
	td.move {
		background-color: #ff000030;
	}
	td.dialog {
		background-color: #00ff0030;
	}
	td.tab {
		background-color: #00a0a030;
	}
	td.ui {
		background-color: #0000ff30;
	}
</style>
<table>
	<tr>
		<td><b>`</b><br /></td>
		<td class="tab"><b>1</b><br /></td>
		<td class="tab"><b>2</b><br /></td>
		<td class="tab"><b>3</b><br /></td>
		<td class="tab"><b>4</b><br /></td>
		<td class="tab"><b>5</b><br /></td>
		<td class="tab"><b>6</b><br /></td>
		<td class="tab"><b>7</b><br /></td>
		<td class="tab"><b>8</b><br /></td>
		<td class="tab"><b>9</b><br /></td>
		<td class="tab"><b>0</b><br /></td>
		<td><b>-</b><br /></td>
		<td><b>=</b><br /></td>
		<td colspan="2"><b>Backspace</b><br />Delete<br /><i>Delete word</i></td>
	</tr>
	<tr>
		<td colspan="2"><b>Tab</b><br /></td>
		<td class="tab"><b>Q</b><br />Close tab<br /><i>Close all tabs</i></td>
		<td><b>W</b><br /></td>
		<td class="dialog"><b>E</b><br />Open file<br /><i>Open workspace</i></td>
		<td class="dialog"><b>R</b><br />Replace<br /><i>Replace in project</i></td>
		<td><b>T</b><br /></td>
		<td class="move"><b>Y</b><br />Line start</td>
		<td class="move"><b>U</b><br />Subword start</td>
		<td class="move"><b>I</b><br />Subword end</td>
		<td class="move"><b>O</b><br />Line end</td>
		<td class="dialog"><b>P</b><br />File palette<br /><i>Command palette</i></td>
		<td><b>[</b><br />Expand Selection</td>
		<td class="move"><b>]</b><br />Matching Bracket</td>
		<td class="ui">
			<b>\</b><br />Toggle left pane<br /><i>Toggle right pane</i><br />(Ctrl: Recent
			Projects)
		</td>
	</tr>
	<tr>
		<td colspan="3"><b>Caps Lock</b><br /></td>
		<td><b>A</b><br />Select line<br /><i>Select all</i></td>
		<td><b>S</b><br />Save<br /><i>Save as</i></td>
		<td><b>D</b><br />Delete<br /><i>Delete word</i></td>
		<td class="dialog"><b>F</b><br />Find<br /><i>Find in workspace</i></td>
		<td class="dialog"><b>G</b><br />Go to line</td>
		<td class="move"><b>H</b><br />←</td>
		<td class="move"><b>J</b><br />↓</td>
		<td class="move"><b>K</b><br />↑</td>
		<td class="move"><b>L</b><br />→</td>
		<td><b>;</b><br />Accept suggestion</td>
		<td class="ui"><b>'</b><br />Toggle bottom pane</td>
		<td colspan="2"><b>Enter</b><br /></td>
	</tr>
	<tr>
		<td colspan="3"><b>Shift</b><br /></td>
		<td><b>Z</b><br />Undo<br /><i>Redo</i></td>
		<td><b>X</b><br />Cut<br /><i>Cut to line end</i></td>
		<td><b>C</b><br />Copy<br /><i>Copy line</i></td>
		<td><b>V</b><br />Paste</td>
		<td><b>B</b><br />Multi-cursor word<br /><i>Multi-cursor below</i></td>
		<td class="tab"><b>N</b><br />New file<br /><i>New window</i></td>
		<td><b>M</b><br />Join Down<br /><i>Join Up</i></td>
		<td class="move"><b>,</b><br />Page up</td>
		<td class="move"><b>.</b><br />Page down</td>
		<td><b>/</b><br />Go to bottom<br /><i>Go to top</i></td>
		<td colspan="3"><b>Shift</b><br /></td>
	</tr>
</table>
<table>
	<tr>
		<td>
			<b>Common</b><br />
			Action<br />
			<i>Shift Action</i>
		</td>
		<td class="move">
			<b>Move</b><br />
			(Shift: selection)
		</td>
		<td class="dialog">
			<b>Dialog</b><br />
			May open a dialog
		</td>
		<td class="tab">
			<b>Tab</b><br />
			Manipulate tabs
		</td>
		<td class="ui">
			<b>UI</b><br />
			Tweaks UI
		</td>
	</tr>
</table>
-->

## Notation

- `A-`: Alt, meta, opt, etc.
- `C-`: Control (or command in Mac)
- `S-`: Shift

## List

Note: Move key with shift is considered as selection (or range) operation.

- `A-a`: Select line
- `A-A`: Select all
- `A-b`: Multiple cursors for words
- `A-B`: Multiple cursors to below
- `A-c`: Copy (If not selected, copy whole line)
- `A-d`: Delete
- `A-D`: Delete a word
- `A-e`: Open file (from 'edit')
- `A-E`: Open workspace (or directory)
- `A-f`: Find
- `A-F`: Find in workspace
- `A-g`: Go to line
- `A-h`: Move left
- `C-A-h`: Backspace
- `A-i`: Move to the subword end
- `A-j`: Move down
- `C-A-j`: Join lines
- `A-k`: Move up
- `A-l`: Move right
- `A-m`: Join line down
- `A-M`: Join line up
- `A-n`: New file
- `A-N`: New window
- `A-o`: Move to the end of the line
- `A-p`: Open file palette
- `A-P`: Open command palette
- `A-q`: Close current tab
- `A-Q`: Close all tabs and panes
- `A-r`: Replace
- `A-R`: Replace in project
- `A-s`: Save
- `A-S`: Save as
- `A-u`: Move to the subword start
- `A-v`: Paste
- `A-x`: Cut (If not selected, cut whole line)
- `A-X`: Cut to the end of line
- `A-y`: Move to the beginning of the line (or the first non-whitespace character)
- `A-z`: Undo
- `A-Z`: Redo
- `A-Backspace`: Erase a word
- `A-[`: Expand selection (e.g. Smart expand)
- `A-]`: Move to matching brackets
- `A-,`: (Half) Page up
- `A-<`: Select (Half) page up
- `A-.`: (Half) Page down
- `A->`: Select (Half) page down
- `A-/`: Move to bottom
- `A-?`: Move to top
- `A-;`: Accept suggestion (autocompletion, copilot, etc.)
- `A-'`: Toggle bottom pane (commonly, integrated terminal)
- `A-"`: Open terminal in editor
- `A-\\`: Toggle left pane (commonly, file tree)
- `A-|`: Toggle right pane
- `C-A-\\`: Recent Project
