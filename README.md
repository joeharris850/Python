# Python
Python Scripts (Educational)
import imaplib
import selenium
import os

server = ‘mail.gmail.com’
user = 'YOUR USERNAME'
password = 'YOUR PASSWORD'
outputdir = 'https://docs.google.com/spreadsheets/d/14Fpv6NYZZ6E2W3zz3fiG0HuzlzQgTDxYUPOqUYuhYZw/edit#gid=0'
subject = ‘[Talkdesk] Your 7 day Calls Report is ready!’

# connects to email client through IMAP
def connect(server, user, password):
    m = imaplib.IMAP4_SSL(server)
    m.login(user, password)
    m.select()
    return m

# click to download using identifierID
# login to TalkDesk with Okta authentication

<a href="https://reporting-explore-email.talkdeskapp.com/files/retrieve?account_id=58c2ffdc717e2800084c3e84&identifier=86f9ecb4d5044d5999bc36f36b225f7b" target="_blank" data-saferedirecturl="https://www.google.com/url?q=https://reporting-explore-email.talkdeskapp.com/files/retrieve?account_id%3D58c2ffdc717e2800084c3e84%26identifier%3D86f9ecb4d5044d5999bc36f36b225f7b&source=gmail&ust=1637666334948000&usg=AOvVaw1xWFsYnAUQiHx4TjwJWStJ">here</a>
