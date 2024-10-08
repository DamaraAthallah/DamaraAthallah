<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Diri</title>
    <style>
        /* CSS styles for the page layout and elements */
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }

        /* Flex container for the profile layout */
        #profile-container {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }

        /* Styling for the profile image */
        #profile-image {
            width: 200px;
            height: 200px;
            border-radius: 50%; /* Creates a circular image */
            object-fit: cover; /* Ensures the image covers the entire area */
        }

        /* Styling for the profile information section */
        #profile-info {
            display: flex;
            flex-direction: column;
            gap: 15px;
            flex: 1;
            min-width: 300px;
        }

        /* Styling for tables used in the profile */
        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }

        th {
            background-color: #f2f2f2;
        }

        /* Styling for the button container */
        .button-container {
            display: flex;
            justify-content: flex-start;
            margin-top: 10px;
        }

        /* Styling for buttons */
        .button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        /* Styling for forms */
        form {
            display: grid;
            gap: 10px;
        }

        input, textarea {
            width: 100%;
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        /* Styling for social media links */
        .social-links {
            display: flex;
            gap: 10px;
        }

        .social-links a {
            text-decoration: none;
            color: #333;
        }
    </style>
</head>
<body>
    <h1>Profile Diri</h1>

    <!-- Main profile container -->
    <div id="profile-container">
        <!-- Profile image section -->
        <div>
            <img id="profile-image" src="damara.jpg" alt="Foto Profil">
        </div>

        <!-- Profile information section -->
        <div id="profile-info">
            <!-- Name section -->
            <h2>Nama:</h2>
            <p>Damara Athallah Rafi Anaudri</p>

            <!-- About Me section -->
            <h2>Tentang Saya:</h2>
            <p>Perkenalkan Nama saya Damara Athallah Rafi Anaudri kelas IT-46-04 jurusan Teknologi Informasi</p>

            <!-- Contact Information section -->
            <h2>Informasi Kontak:</h2>
            <table>
                <tr>
                    <th>Email:</th>
                    <td>damaraathallah@student.telkomuniversity.ac.id</td>
                </tr>
                <tr>
                    <th>Nomor Telepon:</th>
                    <td>+62 812-9391-6507</td>
                </tr>
            </table>

            <!-- Skills section -->
            <h2>Keahlian:</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>

            <!-- Video Introduction section -->
            <h2>Video Perkenalan:</h2>
            <video width="320" height="240" controls>
                <source src="video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>

            <!-- Contact Form section -->
            <h2>Hubungi Saya:</h2>
            <form>
                <label for="nama">Nama:</label>
                <input type="text" id="nama" name="nama" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="pesan">Pesan:</label>
                <textarea id="pesan" name="pesan" rows="4" required></textarea>

                <div class="button-container">
                    <button type="submit" class="button">Kirim</button>
                </div>
            </form>

            <!-- Social Media Links section -->
            <h2>Media Sosial Saya:</h2>
            <div class="social-links">
                <a href="https://github.com/Ergi2003" target="_blank">Github</a>
                <a href="https://www.instagram.com/damara_athallah/" target="_blank">Instagram</a>
            </div>
        </div>
    </div>
</body>
</html>