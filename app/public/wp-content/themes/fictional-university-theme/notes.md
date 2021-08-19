<?php
            if (is_category()) {
                single_cat_title();
            }
            if (is_author()) {
                echo 'Posts by ';
                the_author();
            } ?>

            This will allow me to have fine grain control over what will display on archive pages.