# toowak.github.io
.anchor-highlight {
    font-size: 0.7em;
    margin-left: 0.25em;
}
/* for pageContentMenu */
#md-page-menu {
        position: static;
}
#md-page-menu a.active {
    /* background-color: rgba(0, 0, 0, 0.01); */
    font-weight: bold;
    padding-left: 6px;

}
@media (min-width: 992px) {
    #md-page-menu.affix {
        position: fixed;
    }
}
@media (min-width: 768px) {
    .md-float-left .col-sm-8, .md-float-right .col-sm-8 {
        max-width: 66.67%;
    }
    .md-float-left .col-sm-4, .md-float-right .col-sm-4  {
        max-width: 33.33%;
    }
    .md-float-left .col-sm-2, .md-float-right .col-sm-2 {
        max-width: 16.67%;
    }

}
@media (max-width: 992px) {
    a.forkmeongithub {
        display: none;
    }
}
@media (max-width: 768px) {
    /* don't use floating for smaller screens */
    .md-float-left .col-sm-8, .md-float-left .col-sm-4, .md-float-left .col-sm-2 {
        width: 100%;
        max-width: !important;
        min-width: 100%;
    }
    .md-float-right .col-sm-8, .md-float-right .col-sm-4, .md-float-right .col-sm-2 {
        width: 100%;
        max-width: !important;
        min-width: 100%;
    }
}

.md-floatenv .md-text {
    /* md-text is not of md-col-* but needs the spacing */
    margin-left: 15px;
    margin-right: 15px;
}

/* float images */
.md-float-left .col-sm-8, .md-float-left .col-sm-4, .md-float-left .col-sm-2 {
    width: auto;
}
.md-float-right .col-sm-8, .md-float-right .col-sm-4, .md-float-right .col-sm-2 {
    float: right !important;
    width: auto;
}
#md-all .md-copyright-footer {
    background-color: !important;
    font-size: smaller;
    padding: 1em;
}
</style>
