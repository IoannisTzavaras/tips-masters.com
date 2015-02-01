<?php
/**
 * Tips Masters
 *
 * Η Tips Masters είναι η απόλυτη ιστοσελίδα κοινωνικής δικτύωσης για παίκτες 
 * ποδοσφαιρικού στοιχήματος. Ο χρήστης με την Tips Masters έχει τη δυνατότητα 
 * να δώσει τα στοιχήματα του, να δει τα στοιχήματα των άλλων, να κάνει τα 
 * σχόλια του και να δει τα σχόλια των άλλων για τους αγώνες. Κοινωνικά ο 
 * χρήστης μπορεί να ακολουθήσει άλλους χρήστες, να επικοινωνήσει με άλλους 
 * χρήστες ιδιωτικά και δημόσια. Τέλος η Tips Masters διαθέτει ένα σύστημα 
 * αξιολόγισης για τους χρήστες με το οποίο μπορούν να αναδειχθούν οι κορυφαίοι 
 * χρήστες και αυτό κάνει την Tips Masters ενδιαφέρουσα.
 *
 * Copyright (c) 2015, Ιωάννης Τζαβάρας
 *
 * Permission is hereby granted, free of charge, to any person obtaining a copy
 * of this software and associated documentation files (the "Software"), to deal
 * in the Software without restriction, including without limitation the rights
 * to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 * copies of the Software, and to permit persons to whom the Software is
 * furnished to do so, subject to the following conditions:
 *
 * The above copyright notice and this permission notice shall be included in
 * all copies or substantial portions of the Software.
 *
 * THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 * IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 * FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 * AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 * LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 * OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 * THE SOFTWARE.
 *
 * @package	Tips Masters
 * @author	Ιωάννης Τζαβάρας
 * @copyright	Copyright (c) 2015, Ιωάννης Τζαβάρας ( https://www.facebook.com/tzavaras.g.ioannis )
 * @license	http://opensource.org/licenses/MIT	MIT License
 * @link	http://tips-masters.com
 * @since	Version 1.0.0
 * @filesource
 */
defined('BASEPATH') OR exit('No direct script access allowed');
?>

<!DOCTYPE html>
<html lang="<?= $this->site_language['short']; ?>" xmlns:fb="http://ogp.me/ns/fb#">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel=icon href=<?= site_url('includes/packages/site/images/icon.png'); ?> sizes="16x16" type="image/png">
        <title><?= $this->lang->line('meta_title'); ?></title>
        <meta name="description" content="<?= $this->lang->line('meta_description'); ?>">
        <meta name="keywords" content="<?= $this->lang->line('meta_keywords'); ?>">
        <meta name="author" content="<?= $this->lang->line('meta_author'); ?>">
        
        <meta property="og:title" content="<?= $this->lang->line('og_title'); ?>" />
        <meta property="og:site_name" content="Tips Masters" />
        <meta property="og:url" content="<?= base_url(); ?>" />
        <meta property="og:description" content="<?= $this->lang->line('og_description'); ?>" />
        <meta property="og:image" content="<?= site_url('includes/packages/site/images/fb-post.png'); ?>" />
        <meta property="fb:app_id" content="<?= $this->config->item('fb_app_id'); ?>" />
        <meta property="og:type" content="website" />
        <meta property="og:locale" content="<?= $this->lang->line('og_locale'); ?>" />
        <meta property="og:locale:alternate" content="<?= $this->lang->line('og_alternate_1'); ?>" />
        <meta property="og:locale:alternate" content="<?= $this->lang->line('og_alternate_2'); ?>" />
        
        <link rel="stylesheet" href="<?= site_url('includes/packages/bootstrap/' . $this->config->item('bootstrap_version') . '/css/bootstrap-theme.min.css'); ?>">
        <link rel="stylesheet" href="<?= site_url('includes/packages/site/css/not_connected/nc_main.min.css'); ?>">
        <script >
          window.___gcfg = {
            lang: '<?= $this->site_language['short']; ?>',
            parsetags: 'onload'
          };
        </script>
        <script src="https://apis.google.com/js/platform.js" async defer></script>
    </head>
    <body>
    <script src="<?= site_url('includes/packages/site/js/analytics.min.js'); ?>"></script>
    
