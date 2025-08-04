# WeaponSkinsFork 

Last updated: August 4, 2025 at 3:19:06 AM UTC

* Manifests: [8654541613307577757](https://steamdb.info/depot/2347771/history/?changeid=M:8654541613307577757), [7997552756635206048](https://steamdb.info/depot/2347773/history/?changeid=M:7997552756635206048)
* Repository: https://github.com/sebaselizeche/cs2-WeaponPaints
* Gamedata: https://github.com/sebaselizeche/cs2-WeaponPaints/blob/main/gamedata/weaponpaints.json

## Signatures

### ChangeSubclass

<table>
<tr><th>Status</th><th>Platform</th><th>Library</th><th>CODE-Style</th><th>IDA-Style</th></tr><tr><td>✅</td><td>Windows</td><td>server</td><td>
<pre>
\x48\x89\x6C\x24\x2A\x56\x48\x83\xEC\x2A\x48\x8B\xEA\x48\x8B\xF1\xE8\x2A\x2A\x2A\x2A\x84\xC0\x0F\x84
</pre>
</td><td>
<pre>
48 89 6C 24 ? 56 48 83 EC ? 48 8B EA 48 8B F1 E8 ? ? ? ? 84 C0 0F 84
</pre>
</td></tr><tr><td>✅</td><td>Linux</td><td>server</td><td>
<pre>
\x55\x48\x89\xE5\x41\x55\x41\x54\x49\x89\xF4\x53\x48\x89\xFB\x48\x83\xEC\x2A\xE8\x2A\x2A\x2A\x2A\x84\xC0\x74
</pre>
</td><td>
<pre>
55 48 89 E5 41 55 41 54 49 89 F4 53 48 89 FB 48 83 EC ? E8 ? ? ? ? 84 C0 74
</pre>
</td></tr></table>

### CAttributeList_SetOrAddAttributeValueByName

<table>
<tr><th>Status</th><th>Platform</th><th>Library</th><th>CODE-Style</th><th>IDA-Style</th></tr><tr><td>❌</td><td>Windows</td><td>server</td><td>
<pre>
\x40\x53\x41\x56\x41\x57\x48\x81\xEC\x90\x00\x00\x00\x0F\x29\x74\x24\x70
</pre>
</td><td>
<pre>
40 53 41 56 41 57 48 81 EC 90 00 00 00 0F 29 74 24 70
</pre>
</td></tr><tr><td>✅</td><td>Linux</td><td>server</td><td>
<pre>
\x55\x48\x89\xE5\x41\x57\x41\x56\x49\x89\xFE\x41\x55\x41\x54\x49\x89\xF4\x53\x48\x83\xEC\x78
</pre>
</td><td>
<pre>
55 48 89 E5 41 57 41 56 49 89 FE 41 55 41 54 49 89 F4 53 48 83 EC 78
</pre>
</td></tr></table>

### CBaseModelEntity_SetBodygroup

<table>
<tr><th>Status</th><th>Platform</th><th>Library</th><th>CODE-Style</th><th>IDA-Style</th></tr><tr><td>✅</td><td>Windows</td><td>server</td><td>
<pre>
\x48\x89\x5C\x24\x08\x48\x89\x74\x24\x10\x57\x48\x83\xEC\x20\x41\x8B\xF8\x48\x8B\xF2\x48\x8B\xD9\xE8\x2A\x2A\x2A\x2A
</pre>
</td><td>
<pre>
48 89 5C 24 08 48 89 74 24 10 57 48 83 EC 20 41 8B F8 48 8B F2 48 8B D9 E8 ? ? ? ?
</pre>
</td></tr><tr><td>✅</td><td>Linux</td><td>server</td><td>
<pre>
\x55\x48\x89\xE5\x41\x55\x49\x89\xF5\x41\x54\x41\x89\xD4\x53\x48\x89\xFB\x48\x83\xEC\x08\xE8\x2A\x2A\x2A\x2A\x48\x85\xC0
</pre>
</td><td>
<pre>
55 48 89 E5 41 55 49 89 F5 41 54 41 89 D4 53 48 89 FB 48 83 EC 08 E8 ? ? ? ? 48 85 C0
</pre>
</td></tr></table>

