<script>
    import FaAndroid from 'svelte-icons/fa/FaAndroid.svelte'
    import '../../app.css'
</script>
<div class="overflow-x-auto">
    <table class="table">
      <!-- head -->
      <thead>
        <tr>
          <th></th>
          <th>OS</th>
          <th>Version</th>
          <th>Download</th>
        </tr>
      </thead>
      <tbody>
        <!-- row 1 -->
        <tr class="hover">
          <th>1</th>
          <td><strong>Android</strong></td>
          <td>0.0.1</td>
          <td class="link link-info">Download APK</td>
        </tr>
        <!-- row 2 -->
        <tr class="hover">
          <th>2</th>
          <td>Windows</td>
          <td>0.0.1</td>
          <td class="link link-info">Download exe</td>
        </tr>
        <!-- row 3 -->
        <tr class="hover">
          <th>3</th>
          <td>Linux - Debian</td>
          <td>0.0.1</td>
          <td class="link link-info">Download deb</td>
        </tr>
      </tbody>
    </table>
  </div>