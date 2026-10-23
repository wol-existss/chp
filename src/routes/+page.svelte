<script lang="ts">
    import { Button } from "#lib/components/ui/button";
    import { Badge } from "#lib/components/ui/badge";
    import { Separator } from "#lib/components/ui/separator";
    import * as Sheet from "#lib/components/ui/sheet";
    import * as Carousel from "#lib/components/ui/carousel";
    import * as DropdownMenu from "#lib/components/ui/dropdown-menu";
    import * as Tooltip from "#lib/components/ui/tooltip";
    import * as Tabs from "#lib/components/ui/tabs";
    import * as Dialog from "#lib/components/ui/dialog";
</script>

<header class="w-full">
    <nav class="max-w-6xl mx-auto px-6 py-5 flex items-center justify-between gap-6">
        <a
            href="#home"
            class="font-display text-3xl font-bold text-light-cream shrink-0"
        >
            CHP<span class="text-brand-lavender">.</span>
        </a>

        <div class="flex items-center gap-6">
            <a
                href="#about"
                class="text-sm text-light-cream/80 hover:text-light-cream transition-colors"
                >
                About
            </a>

            <a
                href="#sponsors"
                class="text-sm text-light-cream/80 hover:text-light-cream transition-colors"
                >
                Sponsors
            </a>


            <Button href="#volunteering" size="lg">
                Get Involved
            </Button>

            <a
                href="https://placeholder.ca"
                class="text-sm text-light-cream/80 hover:text-light-cream transition-colors"
                target="_blank"
                rel="noopener noreferrer"
            >
                MNS
            </a>
        </div>
    </nav>
</header>