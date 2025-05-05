---
layout: layout
title: Teacher List
---

<div>
        <div class="container">
            <h1 class="display-4 mb-4">All Teacher</h1>

            <!-- Search Bar -->
            <form method="GET" action="/manager/teachers" class="input-group mb-4">
                <input type="text" name="query" placeholder="Enter search term..." value="" class="form-control">
                <button type="submit" class="btn btn-primary">Search</button>
            </form>

            <table class="table table-hover table-bordered">
                <thead class="table-dark">
                    <tr>
                        <th scope="col">Eamil</th>
                        <th scope="col">User ID</th>
                        <th scope="col">Suspended</th>
                        <th scope="col">Man</th>
                    </tr>
                </thead>
                <tbody>
                    <tr onclick="window.location='/manager/teachers/2/assignments'" style="cursor: pointer;">
                        <td>stefanobianda@ik.me</td>
                        <td>45545d75-ec1e-481c-b9b6-d685adb3aa50</td>
                        <td>false</td>
                        <td>true</td>
                    </tr>
                    <tr onclick="window.location='/manager/teachers/102/assignments'" style="cursor: pointer;">
                        <td>biesse68@gmail.com</td>
                        <td>5b0f1116-c235-44fd-90be-d3d474500d42</td>
                        <td>false</td>
                        <td>true</td>
                    </tr>
                </tbody>
            </table>
            
        </div>
    </div>