  <script>
    import '../app.css';
  </script>

<div class="navbar bg-base-100">
    <div class="flex-1">
      <a href="/" class="btn btn-ghost normal-case text-xl">FeverFlix</a>
    </div>
    <div class="flex-none">
      <ul class="menu menu-horizontal px-1">
        <li><a href="/download"><strong>Download</strong></a></li>
        <li>
          <details class="dropheader">
            <summary>
              Info
            </summary>
            <ul class="p-2 bg-base-100">
              <li><a href="/about">About</a></li>
              <li><a href="https://github.com/voyagerowl/FeverFlix">Contribute</a></li>
            </ul>
          </details>
        </li>
      </ul>
    </div>
  </div>

<slot />
