COSC360G8
=========

Our Project

The objective is to make it easy to create Teams.

	
	This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

Basic:
- students log into a website using their usual credentials (Novell). They enter their name, degree (BA/BSc), major, minor, programming experience (ranked from 1: very low (no experience outside courses) to 5 very good (professional consultant)), list of skills relevant to the course, blacklist, days/time they cannot meet, and (optionally) they select a project.
- instructor log in, enter the number of teams to create, and place students in teams according to the following soft constraints: balance male/female, balance BA/BSc, avoid blacklist, balance experience.

Normal:
- when student enters his data, the camera takes a picture that is uploaded with their profile (see https://developer.mozilla.org/en-US/docs/WebRTC/Taking_webcam_photos for pictures)
- checkbox: remove students from available list after it is placed in a team
- after instructor click create, emails are sent to students informing them of their teams (manual)

Fancy:
- random assignments while respecting blacklist
- optimal assignments using optimation

The reason why there is very little activity on git hub from our accounts is because we were using c9.io. 
We did all of the work together, so each commit is the best representation of the distribution of work. 
