# cs2-inventory-simulator-plugin 

Last updated: August 1, 2025 at 10:42:03 PM UTC

* Manifests: [8654541613307577757](https://steamdb.info/depot/2347771/history/?changeid=M:8654541613307577757), [7997552756635206048](https://steamdb.info/depot/2347773/history/?changeid=M:7997552756635206048)
* Repository: https://github.com/ianlucas/cs2-inventory-simulator-plugin
* Gamedata: https://github.com/ianlucas/cs2-inventory-simulator-plugin/blob/main/gamedata/inventory-simulator.json

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
<tr><th>Status</th><th>Platform</th><th>Library</th><th>CODE-Style</th><th>IDA-Style</th></tr><tr><td>✅</td><td>Windows</td><td>server</td><td>
<pre>
\x40\x53\x55\x41\x56\x48\x81\xEC\x2A\x2A\x2A\x2A\x0F\x29\x74\x24
</pre>
</td><td>
<pre>
40 53 55 41 56 48 81 EC ? ? ? ? 0F 29 74 24
</pre>
</td></tr><tr><td>✅</td><td>Linux</td><td>server</td><td>
<pre>
\x55\x48\x89\xE5\x41\x57\x41\x56\x49\x89\xFE\x41\x55\x41\x54\x53\x48\x89\xF3\x48\x83\xEC\x2A\xF3\x0F\x11\x85
</pre>
</td><td>
<pre>
55 48 89 E5 41 57 41 56 49 89 FE 41 55 41 54 53 48 89 F3 48 83 EC ? F3 0F 11 85
</pre>
</td></tr></table>

### CBaseModelEntity_SetBodygroup

<table>
<tr><th>Status</th><th>Platform</th><th>Library</th><th>CODE-Style</th><th>IDA-Style</th></tr><tr><td>✅</td><td>Windows</td><td>server</td><td>
<pre>
\x48\x89\x5C\x24\x2A\x48\x89\x74\x24\x2A\x57\x48\x83\xEC\x2A\x41\x8B\xF8\x48\x8B\xF2\x48\x8B\xD9\xE8
</pre>
</td><td>
<pre>
48 89 5C 24 ? 48 89 74 24 ? 57 48 83 EC ? 41 8B F8 48 8B F2 48 8B D9 E8
</pre>
</td></tr><tr><td>✅</td><td>Linux</td><td>server</td><td>
<pre>
\x55\x48\x89\xE5\x41\x55\x41\x89\xF5\x41\x54\x41\x89\xD4\x53\x48\x89\xFB
</pre>
</td><td>
<pre>
55 48 89 E5 41 55 41 89 F5 41 54 41 89 D4 53 48 89 FB
</pre>
</td></tr></table>

### CCSPlayerPawn_IsAbleToApplySpray

<table>
<tr><th>Status</th><th>Platform</th><th>Library</th><th>CODE-Style</th><th>IDA-Style</th></tr><tr><td>✅</td><td>Windows</td><td>server</td><td>
<pre>
\x48\x89\x5C\x24\x2A\x48\x89\x74\x24\x2A\x48\x89\x7C\x24\x2A\x4C\x89\x74\x24\x2A\x55\x48\x8D\xAC\x24\x2A\x2A\x2A\x2A\x48\x81\xEC\x2A\x2A\x2A\x2A\x49\x8B\xF1
</pre>
</td><td>
<pre>
48 89 5C 24 ? 48 89 74 24 ? 48 89 7C 24 ? 4C 89 74 24 ? 55 48 8D AC 24 ? ? ? ? 48 81 EC ? ? ? ? 49 8B F1
</pre>
</td></tr><tr><td>✅</td><td>Linux</td><td>server</td><td>
<pre>
\x55\x48\x89\xE5\x41\x57\x41\x56\x49\x89\xD6\x41\x55\x48\x8D\x95\x2A\x2A\x2A\x2A\x49\x89\xCD
</pre>
</td><td>
<pre>
55 48 89 E5 41 57 41 56 49 89 D6 41 55 48 8D 95 ? ? ? ? 49 89 CD
</pre>
</td></tr></table>

### CCSPlayerController_ProcessUsercmds

<table>
<tr><th>Status</th><th>Platform</th><th>Library</th><th>CODE-Style</th><th>IDA-Style</th></tr><tr><td>✅</td><td>Windows</td><td>server</td><td>
<pre>
\x48\x8B\xC4\x44\x88\x48\x20\x44\x89\x40\x18\x48\x89\x50\x10\x53
</pre>
</td><td>
<pre>
48 8B C4 44 88 48 20 44 89 40 18 48 89 50 10 53
</pre>
</td></tr><tr><td>✅</td><td>Linux</td><td>server</td><td>
<pre>
\x55\x48\x89\xE5\x41\x57\x41\x56\x41\x55\x41\x54\x53\x48\x89\xFB\x48\x83\xEC\x2A\x89\x4D
</pre>
</td><td>
<pre>
55 48 89 E5 41 57 41 56 41 55 41 54 53 48 89 FB 48 83 EC ? 89 4D
</pre>
</td></tr></table>

### CCSPlayerController_UpdateSelectTeamPreview

<table>
<tr><th>Status</th><th>Platform</th><th>Library</th><th>CODE-Style</th><th>IDA-Style</th></tr><tr><td>✅</td><td>Windows</td><td>server</td><td>
<pre>
\x89\x54\x24\x2A\x55\x48\x81\xEC
</pre>
</td><td>
<pre>
89 54 24 ? 55 48 81 EC
</pre>
</td></tr><tr><td>✅</td><td>Linux</td><td>server</td><td>
<pre>
\x55\x48\x89\xE5\x41\x57\x41\x56\x41\x55\x41\x54\x53\x48\x89\xFB\x48\x83\xEC\x2A\x89\x75
</pre>
</td><td>
<pre>
55 48 89 E5 41 57 41 56 41 55 41 54 53 48 89 FB 48 83 EC ? 89 75
</pre>
</td></tr></table>

### CServerSideClientBase_SetSignonState

<table>
<tr><th>Status</th><th>Platform</th><th>Library</th><th>CODE-Style</th><th>IDA-Style</th></tr><tr><td>✅</td><td>Windows</td><td>engine2</td><td>
<pre>
\x40\x57\x48\x83\xEC\x2A\x48\x8B\xF9\x48\x89\x74\x24
</pre>
</td><td>
<pre>
40 57 48 83 EC ? 48 8B F9 48 89 74 24
</pre>
</td></tr><tr><td>✅</td><td>Linux</td><td>engine2</td><td>
<pre>
\x55\x89\xF0\x48\x89\xE5\x41\x57\x41\x56\x41\x55\x41\x54\x41\x89\xF4
</pre>
</td><td>
<pre>
55 89 F0 48 89 E5 41 57 41 56 41 55 41 54 41 89 F4
</pre>
</td></tr></table>

### CServerSideClientBase_Connect

<table>
<tr><th>Status</th><th>Platform</th><th>Library</th><th>CODE-Style</th><th>IDA-Style</th></tr><tr><td>✅</td><td>Windows</td><td>engine2</td><td>
<pre>
\x48\x89\x5C\x24\x2A\x48\x89\x6C\x24\x2A\x48\x89\x74\x24\x2A\x57\x41\x54\x41\x55\x41\x56\x41\x57\x48\x83\xEC\x2A\x4C\x8B\xBC\x24
</pre>
</td><td>
<pre>
48 89 5C 24 ? 48 89 6C 24 ? 48 89 74 24 ? 57 41 54 41 55 41 56 41 57 48 83 EC ? 4C 8B BC 24
</pre>
</td></tr><tr><td>✅</td><td>Linux</td><td>engine2</td><td>
<pre>
\x55\x48\x89\xE5\x41\x57\x49\x89\xFF\x41\x56\x41\x89\xCE\x41\x55\x41\xBD
</pre>
</td><td>
<pre>
55 48 89 E5 41 57 49 89 FF 41 56 41 89 CE 41 55 41 BD
</pre>
</td></tr></table>

