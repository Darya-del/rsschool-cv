# Darya Traxel

## Contacts

    Github account: Darya-del
    Discord account: darya_traxel #8395
    E-mail: darya.traxel@gmx.de

## About me

Hi! My name is Darya Traxel. I am a student at the german university "Hochschule Fulda". I have worked as specialist at Minsk City Executive Committee for 3 years. After that I have worked as Business Analyst at Softclub. I am easily trained, goal  and team oriented person. I love setting goals to achieve them successfully by myself. 
## Skills

    HTML
    CSS
    Jira
    JS
    Python
    SAP
    English(A2), Italian(A2), German(C1)

## Example of code
```
@application.route('/getProfile/<userId>', methods=['GET'])
def get_profile(userId):
    profile = execute_query('SELECT * FROM participant INNER JOIN agency ON participant.agency_fk = agency.agency_id WHERE ParticipantId = %s ', userId)
    return jsonify(profile)
```