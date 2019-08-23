# NAME

seafiler - Simple shell script to upload files to seafile

# SYNOPSIS

    seafiler FILES...

# CONFIGURATION FILE

Configuration settings for seafiler are stored in _$HOME/.seafilerrc_

	username=foo@taz.de
	password=quux
	baseurl=https://cloud.seafile.com
	repository=video

seafiler uploads files to your default repository if no other repository
is provided.

# LICENSE

Copyright (C) 2019 Mario Domgörgen <mario@domgoergen.com>

License GPLv3+: GNU GPL version 3 or later
<https://www.gnu.org/licenses/gpl.html> This is free software; you are
free to change and redistribute it.  There is NO WARRANTY, to the
extent permitted by law.
