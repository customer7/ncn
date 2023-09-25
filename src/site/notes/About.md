---
{"dg-publish":true,"permalink":"/about/","created":"2023-09-25T09:01:59.890-07:00","updated":"2023-09-25T09:05:59.632-07:00"}
---

<!DOCTYPE html>
<html>
<head>
    <title>Comment Section</title>
</head>
<body>
    <h1>Post Title</h1>
    <p>This is the content of the post.</p>

    <!-- Comment Section -->
    <h2>Comments</h2>
    <div id="comments">
        <!-- Individual Comment -->
        <div class="comment">
            <p><strong>User 1:</strong></p>
            <p>This is the first comment.</p>
        </div>

        <!-- Another Comment -->
        <div class="comment">
            <p><strong>User 2:</strong></p>
            <p>This is another comment.</p>
        </div>
    </div>

    <!-- Comment Form -->
    <h2>Add a Comment</h2>
    <form id="comment-form">
        <label for="username">Your Name:</label>
        <input type="text" id="username" name="username" required><br>

        <label for="comment">Your Comment:</label>
        <textarea id="comment" name="comment" rows="4" cols="50" required></textarea><br>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
