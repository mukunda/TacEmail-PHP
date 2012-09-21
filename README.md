# ElasticEmail PHP class

A quite minimalistic, but easy to deploy PHP class for EmailMashup.

## Usage

    $email = new TacEmail\Email('username', 'apikey12345', array(
    	'from'      => 'notifications@domain.com',
    	'from_name' => 'Domain.com notificator'
    ));

    $email->send('receiver@gmail.com', 'Hello there!', "Hello!\n\nYou are awesome.\n\nCheers");