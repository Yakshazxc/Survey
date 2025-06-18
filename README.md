<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    <h1>BOBO Survey Form</h1>
    <!-- Create Form -->
    <form id="form">
        <!-- Details -->
        <div class="form-control">
            <label for="name" id="label-name">Name</label>
            <input type="text" id="name" placeholder="Enter your name" />
        </div>
        <div class="form-control">
            <label for="email" id="label-email">Email</label>
            <input type="email" id="email" placeholder="Enter your email" />
        </div>
        <div class="form-control">
            <label for="age" id="label-age">Age</label>
            <input type="text" id="age" placeholder="Enter your age" />
        </div>
        <div class="form-control">
            <label for="role" id="label-role">Which option best describes you?</label>
            <select name="role" id="role">
                <option value="student">Student</option>
                <option value="intern">Intern</option>
                <option value="professional">Professional</option>
                <option value="other">Other</option>
            </select>
        </div>
        <div class="form-control">
            <label>Would you recommend BOBO to a friend?</label>
            <label for="recommed-1">
                <input type="radio" id="recommed-1" name="recommed">Yes
            </label>
            <label for="recommed-2">
                <input type="radio" id="recommed-2" name="recommed">No
            </label>
            <label for="recommed-3">
                <input type="radio" id="recommed-3" name="recommed">Maybe
            </label>
        </div>
        <div class="form-control">
            <label>Languages and Frameworks known
                <small>(Check all that apply)</small>
            </label>
            <label for="inp-1">
                <input type="checkbox" name="inp">BOBO AKO
            </label>
            <label for="inp-2">
                <input type="checkbox" name="inp">HINDI AKO BOBO
            </label>
            <label for="inp-3">
                <input type="checkbox" name="inp">MEDYO BOBO
            </label>
            <label for="inp-4">
                <input type="checkbox" name="inp">BOBO TALAGA
            </label>
            <label for="inp-5">
                <input type="checkbox" name="inp">BOBO SIYA
            </label>
            <label for="inp-6">
                <input type="checkbox" name="inp">NONE OF THE ABOVE
            </label>
            <label for="inp-7">
                <input type="checkbox" name="inp">TAE AKO
            </label>
            <label for="inp-8">
                <input type="checkbox" name="inp">TAE SIYA
            </label>
            <label for="inp-9">
                <input type="checkbox" name="inp">AMOY PUTOK
            </label>
            <label for="inp-10">
                <input type="checkbox" name="inp">BADING AKO
            </label>
        </div>
        <div class="form-control">
            <label for="comment">Any comments or suggestions</label>
            <textarea name="comment" id="comment" placeholder="Enter your comment here"></textarea>
        </div>
        <!-- Submit Button -->
        <button type="submit" value="submit">Submit</button>
    </form>
</body>
</html>
