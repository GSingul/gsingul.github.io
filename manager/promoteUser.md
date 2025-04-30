---
layout: layout
title: Promote Student
---

  <section class="container my-4">
    <h1>Promote Student</h1>

<form class="nav-link text-white" method="GET" action="/manager/promoteUser" class="input-group mb-4">
  <input type="text" name="query" placeholder="Enter search term..." class="form-control">
  <button type="submit" class="btn btn-primary">Search</button>
</form>

    <table class="table table-striped table-bordered">
      <thead class="table-light">
        <tr><th>Email</th><th>Name</th></tr>
      </thead>
      <tbody>
        <tr onclick="window.location='/manager/promoteUser/ID1'" style="cursor: pointer;">
          <td>mail@example.com</td><td>mail@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

